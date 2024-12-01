# Step-by-Step Tutorial: Creating an RDS Instance Easily on AWS

## 1. Sign In to Your AWS Account
- Visit [AWS Management Console](https://aws.amazon.com/console/).
- Enter your **username** and create a **secure password** if you’re logging in for the first time.
- Click **Sign In** to access your account.

## 2. Navigate to the RDS Console
- In the AWS Management Console, locate the **9-squares icon** (Service Menu) at the top-left corner of the page.
- Click on it to open the dropdown menu.
- Search for and select **RDS** to navigate to the RDS (Relational Database Service) console.

## 3. Start the Database Creation Process
- In the RDS Console, click the orange **Create database** button at the top of the page.

## 4. Choose the Database Creation Method
- Under the **Database creation method** section, select **Easy create** to simplify the setup process.

## 5. Select the Database Configuration
- In the **Configuration** section, choose **MySQL** as your database engine.

## 6. Choose the Free Tier DB Instance
- Under the **DB instance size** dropdown, select the **Free tier** option to ensure cost-free usage within AWS Free Tier limits.

## 7. Set the Database Identifier and Username
- In the **DB instance identifier** field, enter a name for your database (e.g., `mydatabase`).
- Specify a **Master username** (e.g., `admin`). You can choose any name as long as it meets AWS constraints.

## 8. Set Up Credentials Management
- Under **Credentials management**, select **Self-managed** (to keep the setup free).
- Create a **Master password** that adheres to AWS's security requirements (e.g., minimum of 8 characters, includes letters, numbers, and special characters).

## 9. Skip EC2 Instance Connection
- When prompted about EC2 instance connection, do not configure this option. Keep it set to **None** as this tutorial focuses on a basic standalone database setup.

## 10. Keep Default Settings
- For the remaining options under Easy Create, retain the default configurations.

## 11. Create the Database
- Scroll to the bottom of the page and click the orange **Create database** button.

## 12. Monitor the Database Creation Process
- After clicking the button, AWS will begin creating your RDS instance.
- You can monitor the status on the **Databases** page. Once the status changes to **Available**, your RDS instance is ready for use!

---

That's it! You've successfully created an RDS instance using Easy Create. You can now connect to your database using a client of your choice, such as MySQL Workbench, or explore AWS's built-in management tools.
