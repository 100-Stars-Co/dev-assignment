# User Story: Vehicle Count Display System

**Background:**

We are working on a new feature for a website
that will display real-time information about vehicles passing by a location based on data from LED advertisement signs.
The LED sign captures the following data:

- Vehicle type (e.g., car, truck, motorcycle)
- Vehicle color (e.g., red, blue, black)

The goal is
to design a system to process this data and display the counts of each vehicle type and color over a defined period.

**Objective:**

As a developer,
I should be able to design the backend system to process vehicle data
and display the aggregated count of vehicle types and colors.
The website will show this information in real-time and allow users to view the counts for a given period
(e.g., the past hour, day, etc.).

---

**Acceptance Criteria**

1. **System Design:**
    - Design a system that processes incoming vehicle data from LED signs.
    - Data will include the vehicle type and color.
    - The system should aggregate and store vehicle counts per vehicle type and color.
    - The user should be able to query the vehicle count for a selected period (e.g., hourly, daily).

2. **Database Structure:**
    - Create a database schema to store vehicle data, with fields for:
        - Vehicle type
        - Vehicle color
        - Timestamp
    - Design the database schema to support efficient querying by vehicle type, color, and period.

3. **API Design:**
   - Implement a RESTful API endpoint that allows users to:
   - Query the count of each vehicle type and color for a selected period.
   - Display the results in a readable format (e.g., “Cars: 50, Trucks: 30, Red: 20”).
   - Use mock data if the database is not yet implemented.

4. **Frontend Display:**
   - The website should show the aggregated vehicle counts for each type and color. 
   - The display should update in real time as new data is processed.
   - Please be strict with the following tools: 
        - Framework: NextJS
        - Language: Typescript
        - CSS: pure TailwindCSS (No UI framework) or pure CSS/SCSS
        - Other utility packages: dayjs, lodash, clsx, etc.
---

**Extra Points:**

- Implement an option to filter vehicle counts by different periods (e.g., the past hour, day, or week). 
- Design the system to scale with increasing data volume from multiple LED signs.

---

Please share your work using a GitHub repository with @BIG-BDGE