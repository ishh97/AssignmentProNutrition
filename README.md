![Logo-nav](https://s3.ap-south-1.amazonaws.com/kalvi-education.github.io/front-end-web-development/Kalvium-Logo.png)

# Kalvium Lab | REACT - Pro Nutrition

## Learning Goals

In this exercise, the goal is to apply as many as possible of the concepts you've just learned:

- props and state in react,
- event handling in react.

### Introduction

You just realized that since the beginning of this year, your diet is not healthy, and it may have an impact on your health (and productivity) now and in the long term.

To take care of the food you eat, you decided to create a nutrition app that will track everything you eat!

![Image description](https://s3.ap-south-1.amazonaws.com/kalvi-education.github.io/front-end-web-development/nutrition-react.gif)

So let's get started!

### Progression 1 | Create `FoodBox` component

Create a `FoodBox` component that takes at least `food` as a prop and displays a box with all the information about an ingredient.

You can use this HTML snippet to display properly the `FoodBox`:

```html
<div className="box">
  <article className="media">
    <div className="media-left">
      <figure className="image is-64x64">
        <img src="https://i.imgur.com/eTmWoAN.png" />
      </figure>
    </div>
    <div className="media-content">
      <div className="content">
        <p>
          <strong>Pizza</strong> <br />
          <small>400 cal</small>
        </p>
      </div>
    </div>
    <div className="media-right">
      <div className="field has-addons">
        <div className="control">
          <input className="input" type="number" value="1" />
        </div>
        <div className="control">
          <button className="button is-info">
            +
          </button>
        </div>
      </div>
    </div>
  </article>
</div>
```

### Progression 2 | Display food

In your `App` component (your main component), display as many `FoodBox` as elements inside the variable `foods`.

### Progression 3 | Implement search bar

Create a `Search` component to perform a search that updates the list of all meal.

### Progression 4 | Create add buttons

On your `FoodBox`, you have an input an "+" button. Use them so that when a user clicks on the button, it adds them on a list. Display the count of that item + the calories associated with that item, and display the details in the format: `x pizza = y calories` --> on the right side of each item.

### Progression 5 | Bonus | Group ingredients

You made an awesome application, but you have found a little problem in the UX. For example, if you click twice on "_Apple_", it will display 2 lines "_1 Apple = 400 cal_" instead of 1 line "_2 Apple = 800 cal_". Fix that problem.

### Progression 6 | Bonus | Allow the user to reset

On the right of each item, add a reset button to let users reset the details of that particular item.

Happy coding! :heart:
