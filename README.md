## Installation ⭐

First, Clone this repo. Both the frontend and the backend need to be installed seperately.
```bash
git clone https://github.com/suryateja001/SpaceAPI.git
```
 
 ```bash
 npm install
 npm run build
 ```

 ## Starting the Development Server
 
 Run the following command in the backend directory to start the development server at `PORT=8000` by default.
 
 ```bash
 cd SpaceAPI
 npm run dev
 ```
 
 This will start the development server at [http://localhost:8000](http://localhost:8000).
 **Note :** If `build` folder doen't exist you will see an error at the baseURL i.e. `/`. Create the `build` folder to fix this issue.
 
 ## Get Contributing 🤩
 First things first, In order to contribute you have to create a Pull Request from your forked repo which is a remote clone of this upstream repository.
 
 1. Click this button at the top of screen to fork this repo, **don't forget to star the              repository!** ⭐⭐

2. Next, clone this repository using
    ```bash
    git clone https://github.com/suryateja001/SpaceAPI.git
    ```

3. It is critical to keep your forked repository in sync with the upstream repository so merge           conflicts can be avoided:
    ```bash
    git remote add upstream https://github.com/suryateja001/SpaceAPI.git
    git fetch upstream
    git pull upstream main
    git push
    ```

4. Create a new branch to work upon
    The branch name must be selected according to the issue
    ```bash
    git checkout -b <branch-name>
    ```

5. After the contribution work is ready, go ahead and add it to the staging area:
    ```bash
    git add -A
    ```

6. Now it is time to commit your changes and sync these changes to the forked repo:
    ```bash
    git commit -m <your_message>
    git push origin <branch-name>
    ```
    **Note :** Branch Name is the branch you created earlier
    
    
**For more details related to installation and requirements please check the README in Backend directory.** 

## License
This API is open source and uses a [BSD license](/LICENSE).
