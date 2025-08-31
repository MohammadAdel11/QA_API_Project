# API Testing Project – Contact List App

## 📌 Project Overview
This project is designed to simulate API testing in a collaborative team environment.  
Over the course of **5 days**, small QA teams (4 members each) will work together following **Scrum practices** to plan, design, and execute API tests for the **Contact List Application**.

---

## 🌀 Agile Approach
We are applying Scrum ceremonies to structure our workflow:

- **Sprint Planning (Day 1, 2 hrs):** Review the project requirements, clarify uncertainties, and distribute tasks among team members.  
- **Daily Stand-up (10 mins each day):** Quick updates on progress, next steps, and blockers.  
- **Sprint Review (Day 5, 1 hr):** Demonstration of completed work and discussion of findings with the group.  

---

## 📅 Weekly Plan
| Day | Focus Area | Deliverables |
|-----|------------|--------------|
| **Day 1** | Requirements Analysis | - Document describing how the UI triggers backend APIs <br> - Trello board created with tasks <br> - Postman workspace set up and shared <br> - List of open questions for clarification |
| **Day 2** | Test Design | - Draft positive and negative API test cases in Excel |
| **Day 3** | Implementation – Setup | - Build Postman collection <br> - Organize APIs into structured folders <br> - Configure environment variables (e.g., baseURL, tokens) |
| **Day 4** | Implementation – Validation | - Add test scripts/assertions in Postman <br> - Run the full collection and fix issues until all tests pass |
| **Day 5** | Presentation | - 20-minute group presentation summarizing deliverables, results, and challenges |

---

## 📂 Application Under Test
- **System:** Contact List Application  
- **API Docs:** Contact List API Documentation  

**Team Split:**  
- Team 1 → Contacts APIs  
- Team 2 → Users APIs  

---

## 🛠️ Tools
- [Postman](https://www.postman.com/)  
- Trello (task tracking)  
- Microsoft Excel (test case design)  
- GitHub (project repository)  

---

## 🔧 Guidelines
- Create a dedicated Postman workspace and invite the team.  
- Use Trello to break down APIs into cards and assign ownership.  
- Structure Postman collection properly with folders and clear naming.  
- Implement **assertions** in the *Tests* tab using JavaScript.  
- Rely on **environment variables** for tokens, base URLs, and IDs.  
- Push all deliverables (docs + Postman collections) to GitHub.  

---

## 📝 Examples
- **Positive Test:** `POST /contacts` with valid JSON body → expect 201 Created.  
- **Negative Test:** `POST /contacts` with missing required field → expect 400 Bad Request with error message.  

---

## 🔍 Key Note
Always cross-check API responses with the UI flow to ensure proper mapping between frontend actions and backend behavior.
