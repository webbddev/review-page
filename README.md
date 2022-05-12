### _Review page with prev and next_ project

> _Review_ component with prev and next functionality.

<!-- > Live demo [_here_](https://www.example.com). If you have the project hosted somewhere, include the link here. -->

<!-- <hr style="border:1px dotted lightblue"> </hr> -->

##### General Information

- Purpose of the project is to train myself on using useState and manipulating local data

![](public/My%20Video.gif)

##### Technologies Used

- React.Js

##### Code Elements

- Destructuring data properties and their reference to data index
- Prev/next code (sample below):

<!-- ![](public/code.png)) -->

```javascript
const nextPerson = () => {
  setIndex((index) => {
    let newIndex = index + 1;
    return checkNumber(newIndex);
  });
};
```

##### Installation and project setup

After you clone this repo to your desktop, go to its root directory and run `npm install` to install its dependencies.

Once the dependencies are installed, you can run `npm start` to start the application. You will then be able to access it at `localhost:3000`

##### Acknowledgements

Credits to an awesome instructor John Smilga!
