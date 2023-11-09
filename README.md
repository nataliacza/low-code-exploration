# Low-Code Exploration
Example project made on low-code platform (free to use plans). My main goal was to explore low-code platform possibilities and tooling.


## Retool
Official site: https://retool.com/

- <strong>Project Title:</strong> Softball Team Playground
- <strong>Usage:</strong> Internal resources for softball team
- <strong>Link to page:</strong> [Softball Team Playground](https://natka.retool.com/apps/19574222-7bfb-11ee-a3ef-ffa5d0c46abc/Softball%20Team%20Playground) => <em>At the moment Retool does not offer public page.</em>



### Event Calendar
![image](https://github.com/nataliacza/low-code-exploration/assets/68182069/4991d535-036f-4732-909c-e904c7f56bfb)

- Calendar component uses `PostgreSQL` Retool Database resource. SQL query retrieves data from `softball_events` table and maps it to the component (including joining tables).
- User can add new event via form. Form includes query to fetch data from `event_categories` table to extract categories and link event to existing category ID.
- After successfull form submission, `addNewEvent` query is triggered - using dynamic variables provided in form.

See video:
![chrome_aSbx5ZbrlE](https://github.com/nataliacza/low-code-exploration/assets/68182069/c3e3eabf-644f-4ef4-aad6-8d4a7690f94a)

### The Team
![image](https://github.com/nataliacza/low-code-exploration/assets/68182069/1e8cdb1e-e201-429b-9871-d5b4177f4251)

- Table component uses `Goggle Sheets` resource. Query retrieves data from sheet and maps it to the table.
- User can add new member. Form includes query to fetch data from `Positions` Tab and validates `Number` field (unique values).
- User can update member details. Form is pre-filled with existing member data.
- Additional `JavaScript` function lists all unavailable numbers, so user can check which numbers are taken.
- After successfull form submission, `addNewMember` or `updateMember` query is triggered - using dynamic variables provided in form.

See video:
![chrome_h0ic6qsnmS](https://github.com/nataliacza/low-code-exploration/assets/68182069/4605b93f-dcb8-45c3-895e-51f3c637a6b7)

### Education
![image](https://github.com/nataliacza/low-code-exploration/assets/68182069/27d8e5f9-e9b1-4d92-8256-adc8f778f604)

- Movies component uses `Goggle Sheets` resource. Query retrieves data from sheets.
- Available different tabs and pagination.

