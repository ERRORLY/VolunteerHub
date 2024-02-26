# VolunteerHub 

## RUN ON LOCAL

To run a Next.js project that you've cloned from a GitHub repository, you'll typically follow these steps:

1. **Clone the Repository:** Make sure you have Git installed on your system. Then, clone the repository using the command:

    ```bash
    git clone https://github.com/ERRORLY/VolunteerHub.git
    ```

2. **Navigate to the Project Directory:** Use the `cd` command to navigate into the directory of your cloned project:

    ```bash
    cd VolunteerHub
    ```

3. **Install Dependencies:** Next.js projects usually have dependencies listed in a `package.json` file. To install them, run:

    ```bash
    npm install
    ```

4. **Setup Database**
   
   go to [mongodb atlas](https://www.mongodb.com/atlas)
    and click on try free than register with your google account 

    Now follow this youtube [video](https://youtu.be/PEMfsqZ2-As?t=1634) from 27:14 to 26:29 now you will get a MONGODB_URI than copy that and paste it in this [line](https://github.com/ERRORLY/VolunteerHub/blob/main/lib/mongodb.js#L3)

6. **Run the Development Server:** Next.js comes with a built-in development server that you can start with:

    ```bash
    npm run dev
    ```

5. **Access Your Application:** Once the development server is running, you should be able to access your Next.js application by visiting [http://localhost:3000](http://localhost:3000) in your web browser.

This README provides a step-by-step guide to set up and run the project locally.

```markdown
# Additional Notes

- If you encounter any issues or errors, please check the troubleshooting section in the documentation.
- Contributions are welcome! Feel free to submit a pull request.
