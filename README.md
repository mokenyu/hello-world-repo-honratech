## OFFICIAL LEARNING REPOSITORY FOR THE GENAI TRACK: HONRATECH BOOTCAMP

### Getting Started

- Create your [fork](https://github.com/mokenyu/learning-genai-honratech/fork)
- Clone the repo.
- Create new remote called `upstream` to handle syncing with the forked repo.
    ```
    git remote add upstream https://github.com/mokenyu/learning-genai-honratech
    ```

 - Pull latest changes.
    ```
    git pull upstream main
    ```
 
 - Create a branch with your name and switch to it
    ```
    git checkout -b branch_with_your_name
    ```


### Environment Setup

Run the following commands from project root in your teminal:

- Create virtual environment using `uv`.
    ```
    uv venv
    ```

- Install dependencies and equip environment.
    ```
    uv sync
    ```

 - Create a folder with your name in root.

> For any files you want to make a change to, copy that file to the personal folder you just created and modify unless asked otherwise... whether it's during a training session or you experimenting.
> This is to ensure that the changes of the author and yours do not conflict.