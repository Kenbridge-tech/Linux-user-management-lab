# Executive Summary

 ### Objective:

This lab gave me the opportunity to practice **end-to-end user lifecycle management** in Linux. The main goal was to show how **authentication**, **authorization**, and **account deprovisioning** directly support cybersecurity responsibilities.

---

### Scope:

I worked through four real-world scenarios in this simulation:

1. **Onboarding** – Adding a new employee (researcher9) to the system.

2. **Access Control** – Assigning project file ownership to ensure proper access.

3. **Role Change** – Expanding permissions by adding the employee to a secondary group.

4. **Offboarding** – Safely deleting the employee’s account and group after they left.

### Findings:

From this lab, I observed that:

- User management in Linux requires elevated (sudo) privileges.

- Group memberships can be both primary (one main group) and secondary (supplementary groups).

- File ownership changes are essential when assigning responsibility for projects.

- Proper account cleanup is critical to avoid orphaned accounts or credentials that could pose security risks.

### Recommendations:

Based on the lessons from this exercise, I recommend:

- Always confirm group membership with groups username.

- Run periodic audits of all users and groups.

- Apply the principle of least privilege when assigning roles.

- Immediately disable or delete accounts when employees leave the organization.
