# React State Implementation

## Introduction
Today we will be creating an application that will make a request to the Star Wars api for some random characters and it will update the state of our application to display said characters. We will then add functionality to retrieve other characters and therefore update the state of our application to display the new characters. It's going to be awesome! (Styling not necessary, but it would be nice if you add some).

## Application state
This one is rather simple. Our app state is going to be an object with just one property named ```characters``` it should be initialized as an empty ```array```.

## Components.
Our App will be built with the following components: Header (should display as a navigation bar, it will consist of a button to fetch random characters)
1. ```App```, should handle the state of our application, this component is in charge of setting the initial state of our application by performing an axios request to the Star Wars API as soon as the component is mounted (Hint: Lifecycle methods). This component should render the ```Characters``` component as well.
2. ```Characters```, should recieve the state property ```characters``` of our application as a ```prop```. ```Characters``` is also in charge of rendering 3 instances of the ```Character``` component.
3. ```Character```, is in charge of rendering a character, said character is one of the elements of our state ```characters``` property.

## Disclaimer.
If you feel comfortable, or mildly challenged, while doing this implementation block and the implementation block for React Router, then pat yourself in the back because this is basically all of React. You now know all that you need to be a dangerous React developer.
