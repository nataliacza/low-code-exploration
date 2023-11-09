# Low-Code Exploration
Example project made on low-code platform (free to use plans). My main goal was to explore low-code platform possibilities and tooling.


## Retool
Official site: https://retool.com/

- <strong>Project Title:</strong> Softball Team Playground
- <strong>Usage:</strong> Internal resources for softball team
- <strong>Link to page:</strong> [Softball Team Playground](https://natka.retool.com/apps/19574222-7bfb-11ee-a3ef-ffa5d0c46abc/Softball%20Team%20Playground) => <em>At the moment Retool does not offer public page.</em>



### Event Calendar
- Calendar component uses `PostgreSQL` Retool Database resource. SQL query retrieves data from `softball_events` table and maps it to the component (including joining tables).
- User can add new event via form. Form includes query to fetch data from `event_categories` table to extract categories and link event to existing category ID.
- After successfull form submission, `addNewEvent` query is triggered - using dynamic variables provided in form.

See video:
![chrome_aSbx5ZbrlE](https://github.com/nataliacza/low-code-exploration/assets/68182069/c3e3eabf-644f-4ef4-aad6-8d4a7690f94a)

### The Team
- Table component uses `Goggle Sheets` resource. Query retrieves data from sheet and maps it to the table.
- User can add new member. Form includes query to fetch data from `Positions` Tab and validates `Number` field (unique values).
- User can update member details. Form is pre-filled with existing member data.
- Additional `JavaScript` function lists all unavailable numbers, so user can check which numbers are taken.
- After successfull form submission, `addNewMember` or `updateMember` query is triggered - using dynamic variables provided in form.

See video:
![chrome_mnI5F20wC3](https://github.com/nataliacza/low-code-exploration/assets/68182069/8f442ccd-a776-405e-8127-a1aa9b55d408)

### Education
- Movies component uses `Goggle Sheets` resource. Query retrieves data from dedicated sheets.
- Available pagination and different tabs.

See video:
![chrome_YCSGbeRJDa](https://github.com/nataliacza/low-code-exploration/assets/68182069/f6c79f73-fe38-4eef-a224-ecce8864df99)
