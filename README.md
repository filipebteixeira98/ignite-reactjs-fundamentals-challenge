<img alt="Ignite" src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F2fbacb7a-e460-44a3-8fc5-e66f96dae148%2Fcover-reactjs.png?table=block&id=51e4099a-6e2f-4d4b-ae94-f9fe75bb769d&width=5120&userId=1b109781-8635-4162-80d6-714377721793&cache=v2" />

<h3 align="center">
Challenge 01: ReactJS Concepts
</h3>

<p align="center">
  <img alt="Languages" src="https://img.shields.io/github/languages/count/filipebteixeira98/ignite-reactjs-fundamentals-challenge?color=%235963C5" />
  <img alt="repo-size" src="https://img.shields.io/github/repo-size/filipebteixeira98/ignite-reactjs-fundamentals-challenge?color=%235761C3" />
  <img alt="lastcommit" src="https://img.shields.io/github/last-commit/filipebteixeira98/ignite-reactjs-fundamentals-challenge?color=%235761C3" />
  <img alt="License" src="https://img.shields.io/github/license/filipebteixeira98/ignite-reactjs-fundamentals-challenge?color=%235E69D7" />
  <img alt="Issues" src="https://img.shields.io/github/issues/filipebteixeira98/ignite-reactjs-fundamentals-challenge?color=%235965E0">
  <a href="mailto:filipebarrosteixeira98@gmail.com">
   <img alt="Email" src="https://img.shields.io/badge/-filipebarrosteixeira98%40gmail.com-%23525DCB" />
  </a>
</p>

## :rocket: About the challenge

In this challenge, you will have to create an application to train what you have learned so far in ReactJS
This will be an application where your main objective is a small application of activities to do, to train a little more about state manipulation in React.

## :wrench: Application features

- Add a new task: It must be possible to add a new task in the task state, with the fields id which must be generated randomly, title which must be text and isComplete which must start as false.
- Remove a task: You must receive an ID by parameter and remove the task that contains that ID from the state.
- Mark and unmark a task as completed: You must change the status of isComplete for a task with a specific ID that is received by parameter.

## :syringe: Testing specification

For this challenge, we have the following tests:

- **should be able to add a task**: In order for this test to pass, you must allow the task to be created and thus displayed on the screen. The created taks must contain the attributes following the standard of the interface.

- **should not be able to add a task with an empty title**: For this test to pass, before creating a new task, you must validate that something was typed in the input and do not allow the creation of the task if the value be empty, if the value entered is empty, you must prevent the creation of the task.

- **should be able to remove the task**: In order for this test to pass, you must allow that when clicking on the button with a trash icon, the task related to that button is removed from the state of the application, consequently being removed from the screen.

- **should be able to check a task**: For this test to pass, you must allow that when clicking on the checkbox next to the task, it is marked as completed or not completed according to its current state, changing its value from `isComplete` to `false` to `true` or conversely, from `true` to `false`.

# :page_facing_up: License

This project is under a license [MIT](./LICENSE).

Challenge proposed with 💜 by Rocketseat 👋 [Join this great community!](https://discordapp.com/invite/gCRAFhc)
