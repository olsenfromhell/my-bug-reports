### I. When the question-mark sign is pressed, tooltip does not disappear after scrolling or going back to prev. page

```text
Preconditions: Logged in into LD CRM using [Browser Name, Version]

Steps:
1. Go to Traffic - Users section;
2. Select any User;
3. Scroll down to Status section;
4. Press question-mark sign;
5. Tooltip appears;
6. Go back to previous page.

Expected result: Tooltip is closed after scrolling or going back to the previous page.
Actual result: Tooltip remains.

Check screenshot and video in comments for visualization.

```

### II. When changing elements in Columns section, it's value becomes "Empty"

```text
Preconditions: Logged in into LD CRM using [Browser Name, Version]

Steps to reproduce:
1. Go to Reports - Templates - Default template;
2. Press "Create new template" button;
3. In Columns section, select several values (not all of them);
4. Select any conditions;
5. Press "Apply" button. Template is created;
6. Press "Edit" button on the created template. All values in the Columns section are selected as active, and there are no conditions now;
7. Unselect several values in the Columns section;
8. Press "Apply" button;

Expected result: Values in Columns section and Conditions section are saved as selected. Columns section values are shown as saved.
Actual result: Values in Columns section and Conditions section are not saved. Column section values are shown as "Empty".

For a visual example, check the video below.
```

### III. Eternal loader after clicking on "Go to Customer Area" button using Firefox

```text
Preconditions:
1. Go to https://example.com using Mozilla Firefox [Version].
2. Authorization window is opened.

Steps:
1. Enter the test phone number in the "Phone" field;
2. Enter the test password in the "Password" field;
3. Press "Login" button. Logged in to the system as Test User;
4. Press "Go to Customer Area" button.

Expected result: You are redirected to https://example.com/home page, logged in as Test User.
Actual result: You are not redirected to https://example.com/home page. Eternal loader is shown.

Comment: The same bug occurs when you click on the “Log out” button on the home page after logging in.
