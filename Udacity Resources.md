```
var myCustomDiv = document.createElement('div');

function respondToTheClick(evt) {
    if (evt.target.nodeName === 'P'){
        console.log('A paragraph was clicked: ' + evt.target.textContent);
    }
    
}

for (var i = 1; i <= 200; i++) {
    var newElement = document.createElement('p');
    newElement.textContent = 'This is paragraph number ' + i;

    myCustomDiv.appendChild(newElement);
}

document.body.appendChild(myCustomDiv);

myCustomDiv.addEventListener('click', respondToTheClick);
```

This package has installed:

-   Node.js v12.14.1 to /usr/local/bin/node
-   npm v6.13.4 to /usr/local/bin/npm

Make sure that /usr/local/bin is in your $PATH.


### [用 Git 进行版本控制](https://cn.udacity.com/course/version-control-with-git--ud123)
学习如何使用 Git，这个每名开发者都需要掌握的流行版本控制系统。
### [GitHub 协作](https://cn.udacity.com/course/github-collaboration--ud456)
学习如何与其他开发者一起在 GitHub 上协作。

### [HTML and CSS Syntax](https://cn.udacity.com/course/html-and-css-syntax--ud001)

### [Web 开发者的网络入门](https://cn.udacity.com/course/networking-for-web-developers--ud256)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQxNDQ1Njk0LDc3OTI1Njk2Nl19
-->