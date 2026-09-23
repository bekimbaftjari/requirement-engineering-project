# Week 1 — Initial Discovery

# 1. Facts
.The college has shared equipment.
. Bookings are done by email, spreadsheets and other arrangements.
. Equipment can be double booked.
. People are sometimes not sure if equipment is available.
. Staff spend time checking bookings.
. Equipment is sometimes not returned on time.

# 2. Assumptions

. Students and staff will need to book equipment.
. Equipment needs to be returned after use.
. Some equipment will be used more than others.
. There are rules for borrowing equipment.

# 3. Unknowns

. Who can book equipment?
. How long can equipment be booked for?
. Who checks the bookings?
. What happens if equipment is returned late?

# 4. Stakeholders

| Stakeholder     | What they might need         |
| --------------- | ---------------------------- |
| Students        | Easy way to book equipment   |
| Staff           | Easier way to check bookings |
| Equipment staff | Know where equipment is      |
| Lecturers       | Equipment for classes        |
| College         | Equipment to be looked after |

Possible conflict*
Students might want to keep equipment longer, while staff might need it back for someone else.

# 5. Goals

The system should help the college to:
. Stop equipment being double booked.
. Make it easier to see what equipment is available.
. Make checking bookings easier for staff.

#6. Scope
# In scope
. Checking if equipment is available.
. Booking equipment.
. Recording when equipment is returned.

# Out of scope / not known yet

. Making a mobile app.
. Making a website.
. Deciding what technology to use.

# 7. Candidate Requirements
# Functional Requirements

. The system shall show if equipment is available.
. The system shall let users book equipment.
. The system shall save bookings.
. The system shall record when equipment is returned.

# Non-Functional Requirements
. The system shall keep booking information safe.
. The system shall be easy to use.

# 8. Requirement Surgery

# R1: The system should be easy to use.
Why is it weak?
It does not explain what "easy" means.

**Improved:**
The system shall let users make a booking using simple steps.

### R2: The system should be secure.

**Why is it weak?**
It does not explain what needs to be protected.

**Improved:**
The system shall only let authorised users manage bookings.

## 9. Reflection
I learned that we should understand the problem before deciding on a solution. I also learned the difference between facts, assumptions and unknowns.re sent.

4. Functional Requirements
Requirement

Source

How could we verify it?

FR-01: The system shall allow an authorised user to view equipment availability for a selected date.

Technician

See if the equipment shows as available.

FR-02: The system shall allow an authorised user to book equipment.

User

Try to book equipment.

FR-03: The system shall allow an authorised user to see their bookings.

User

Check if their bookings are there.

5. Quality Requirements
NFR-01
Quality requirement:
Only authorised users can see booking information.

Why does it matter?
To keep the information private.

How could it be checked?
Try to access it without logging in.

6. Project Application
Candidate requirement:
The system shall allow students to view their information.

Source:
Student

Type:
Functional requirement

Clarification question:
What information do students need to see?

Verification:
Check if the information can be viewed.

Unknown:
What information students need.

Who could provide the information?
Students or college staff.

7. Reflection
1. What makes a requirement difficult to understand?
If it is too vague or missing information.

2. What information do you still need for your project?
What information students need.

3. Who could provide that information?
Students or college staff.


