# Low-Code Exploration
Example projects made on <strong>low-code platforms</strong> (free to use plans). My main goal was to explore low-code platforms possibilities and tooling.


## Retool

Official tool site: https://retool.com/

- <strong>Project Title:</strong> Softball Team Playground
- <strong>Usage:</strong> Internal resources for softball team
- <strong>Link to page:</strong> [Softball Team Playground](https://natka.retool.com/apps/19574222-7bfb-11ee-a3ef-ffa5d0c46abc/Softball%20Team%20Playground) => <em>At the moment Retool does not offer public page.</em>

<details><summary>Read more...</summary>


### Event Calendar
- Calendar component uses `PostgreSQL` Retool Database resource. SQL query retrieves data from `softball_events` table and maps it to the component (including joining tables).
- User can add new event via form. Form includes query to fetch data from `event_categories` table to extract categories and link event to existing category ID.
- After successfull form submission, `addNewEvent` query is triggered - using dynamic variables provided in form.

See video:
![retool-01-calendar](https://github.com/nataliacza/low-code-exploration/assets/68182069/cd7b7f0b-ceb7-46e5-83cb-fe3f7c4faacd)

### The Team
- Table component uses `Goggle Sheets` resource. Query retrieves data from sheet and maps it to the table.
- User can add new member. Form includes query to fetch data from `Positions` Tab and validates `Number` field (unique values).
- User can update member details. Form is pre-filled with existing member data.
- Additional `JavaScript` function lists all unavailable numbers, so user can check which numbers are taken.
- After successfull form submission, `addNewMember` or `updateMember` query is triggered - using dynamic variables provided in form.

See video:
![retool-02-team](https://github.com/nataliacza/low-code-exploration/assets/68182069/b1159722-0386-4400-99e4-d95e5823c9df)

### Education
- Movies component uses `Goggle Sheets` resource. Query retrieves data from dedicated sheets.
- Available pagination and different tabs.

See video:
![retool-03-excercises](https://github.com/nataliacza/low-code-exploration/assets/68182069/91720128-a5de-4a41-9e43-dbd8f4c8c6a1)

</details>



## Mendix

Official tool site: https://www.mendix.com/

- <strong>Project Title:</strong> LearnNow Training Management (product of <em>Rapid Developer Training Path</em>)
- <strong>Usage:</strong> Manage courses with access for users with different roles
- <strong>Link to page:</strong> [LearnNow](https://learnnowtrainingmanagement22464-sandbox.mxapps.io/index.html?profile=Responsive)

<details><summary>Read more...</summary>

You can login to application using different accounts, with different access rights:

```
demo_administrator
6p0R9tDJdpQy

demo_teacher
JfIY7TTUCBj2

demo_trainee
G9DrM2MBxbEE
```

### Main Page
![chrome_yb8N1ZcfVk](https://github.com/nataliacza/low-code-exploration/assets/68182069/3fbd5430-5227-4c5a-b7d8-ed623e518a40)

### Courses
![chrome_xG6MkwNqaX](https://github.com/nataliacza/low-code-exploration/assets/68182069/8af5a349-15c8-46ab-b994-c8f561a467c9)

### Locations
![chrome_TQjqTLYoij](https://github.com/nataliacza/low-code-exploration/assets/68182069/f387582a-8d2d-4a63-9242-a5a1f731b39f)

### Teachers
![chrome_48fuW4B0iS](https://github.com/nataliacza/low-code-exploration/assets/68182069/77d4586a-7b8a-4e14-8bf8-042de188df95)

### Trainees
![chrome_bbNmKtYV0l](https://github.com/nataliacza/low-code-exploration/assets/68182069/0a383ca6-613d-431d-baf4-fadbd304d18d)

### Training Event
![chrome_5jncCfbjeM](https://github.com/nataliacza/low-code-exploration/assets/68182069/56a5b4ef-9c26-4574-831c-b7c4e03a39f1)

</details>
