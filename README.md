# IAM-Lab-2-ADD-USER-TO-A-GROUP-
https://www.youtube.com/watch?v=f47aqr6aSrY

# Create a Group (Developers) in AWS IAM

Log in to AWS Console

Go to IAM (Identity and Access Management)

In the left panel → click User groups

Click Create group

# Step 1: Name the Group

Enter group name:
developers

👉 Click Next

 # Step 2: Attach Permissions

Here’s the key part for your lab:

Do NOT select any policy

Just leave everything unchecked.

👉 Click Next

# Step 3: Review & Create

Verify:

Group name: developers

No policies attached

👉 Click Create group

Add Existing Users to the Group

Now you already have users, so let’s attach them.

Go to User groups

Click on developers

Click Add users

Select the users you already created
(tick the checkbox next to usernames)

👉 Click Add users

# Final Result

Group developers is created

No permissions (empty group)

Users are successfully added to the group

# Important Understanding (very useful for interview)

Here’s the thing:

A group without policies = no permissions

Users inside that group = still no permissions

What this really means is:
👉 Group is just a container until you attach a policy
