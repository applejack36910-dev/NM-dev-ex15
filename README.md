# NM-dev-ex15
**Exercise 15 – Binding SonarQube Rules to SonarLint**

**Aim:** To connect the Eclipse project with the SonarQube server and bind the project to analyze code using SonarLint.

**Steps:**

1. Start the SonarQube server and open `http://localhost:9000`.
2. Open the existing **Calculator** project in SonarQube.
3. Open Eclipse and select **Window → Show View → Other**.
4. Search for **SonarQube Bindings** and open the view.
5. Create a new SonarQube server connection.
6. Enter the local server URL: `http://localhost:9000`.
7. Authenticate using the SonarQube user token and complete the connection setup.
8. In the SonarQube Bindings view, locate the **Calculator** project.
9. Bind the Eclipse Calculator project to the SonarQube project named **Calculator** (project key: `calculator`).
10. Right-click the Calculator project in Eclipse and select **SonarQube → Analyze**.
11. Wait for the analysis to complete.
12. Open **SonarLint On-the-fly** and check the analysis results.

**Result:** Successfully connected Eclipse to the SonarQube server, bound the Calculator project, and performed code analysis using SonarLint.
