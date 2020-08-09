## I. LD - when the question-mark sign is pressed, tooltip does not disappear after scrolling or going back to prev. page

```text
Preconditions: Logged in into LD CRM

Steps:

1. Go to Traffic - Users section;
2. Select any User;
3. Scroll down to Status section;
4. Press question-mark sign;
5. Tooltip appears;
6. Go back to previous page.

Expected result: tooltip is closed after scrolling or going back to prev. page.
Actual result: tooltip remains.

Check screenshot and video in comments for visualization.
```

## II. LD - Reports - Templates -  Default template - when changing elements in Columns section, it's value becomes "Empty"

```text
Preconditions: Logged in into LD CRM

Steps to reproduce:

1. Go to Reports - Templates - Default template;
2. Press "Create new template" button;
3. In Columns section select several values (not all of them);
4. Select any conditions;
5. Press "Apply" button. Template created;
6. Press "Edit" button on created template. All of the values in Columns section
are selected as active and there are no conditions now;
7. Unselect several values in Columns section;
8. Press "Apply" button;
9. Columns section values are now shown as "Empty".

Expected result: Values in Columns section and Conditions section are saved as selected. Columns section values are shown as saved.
Actual result: Values in Columns section and Conditions section are not saved. Column section values are shown as "Empty".

For visual example check video below.
```

## III. Demo - Eternal loader after clicking on "Go to Customer Area" button using Firefox

```text
Preconditions:
1. Go to https://example.com using Mozilla Firefox.
2. Authorization window is opened.

Steps:

1. Enter the test phone number in the "Phone" field;
2. Enter the test password in the "Password" field;
3. Press "Login" button. Logged in to the system as Test User;
5. Press "Go to Customer Area" button.

Expected result: you have been redirected to https://example.com/home page, logged in as Test User.
Actual result: you have not been redirected to https://example.com/home page. Eternal loader is shown.

Comment: the same bug is accured when you click on “Log out” button on the home page after logging in.
