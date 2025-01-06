<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png"/>
</p>

# Configuring osTicket: Post-Installation Setup

This guide provides a detailed walkthrough for configuring osTicket after installation. Follow these steps to set up roles, departments, agents, users, and more.

---

## Tools and Technologies Used

- **Operating Systems**: Windows 10 (21H2)
- **Platforms**: Microsoft Azure (Virtual Machines), Remote Desktop Protocol (RDP)
- **Software**: Internet Information Services (IIS)

---

## Overview of Steps

1. **Configure Roles**  
   - Define permissions for agents based on their roles and responsibilities.

2. **Configure Departments**  
   - Organize agents into departments to streamline ticket management.

3. **Configure Teams**  
   - Create specialized teams for more efficient ticket handling.

4. **Allow Ticket Creation by Users**  
   - Adjust settings to enable users to submit tickets without registration.

5. **Add Agents**  
   - Set up agent profiles to manage and respond to tickets.

6. **Add Users**  
   - Register customers who will create support tickets.

7. **Configure SLA Plans**  
   - Define Service Level Agreements to set ticket response time policies.

8. **Define Help Topics**  
   - Add predefined topics to categorize tickets efficiently.

---

## Configuration Steps

### Step 1: Configure Roles

- Navigate to **Admin Panel > Agents > Roles**.
- Create a new role, such as **Supreme Admin**, and set appropriate permissions.

<p align="center">
<img src="https://i.imgur.com/SXpTf20.png" alt="Roles Configuration"/>
<img src="https://i.imgur.com/9fBmrZj.png" alt="Permissions"/>
<img src="https://i.imgur.com/1sDBsuZ.png" alt="More Permissions"/>
</p>

---

### Step 2: Configure Departments

- Go to **Admin Panel > Agents > Departments**.
- Add a new department, such as **System Administrators**.

<p align="center">
<img src="https://i.imgur.com/83gWQsO.png" alt="System Administrators"/>
</p>

---

### Step 3: Configure Teams

- Navigate to **Admin Panel > Agents > Teams**.
- Create a team, like **Level II Support**, for specialized tasks.

<p align="center">
<img src="https://i.imgur.com/BnPrcDH.png" alt="Level II Support"/>
</p>

---

### Step 4: Allow Ticket Creation by Users

- Go to **Admin Panel > Settings > User Settings**.
- Ensure the option **Require registration and login to create tickets** is not selected.

<p align="center">
<img src="https://i.imgur.com/QsJjOuM.png" alt="User Settings"/>
</p>

---

### Step 5: Add Agents

- Navigate to **Admin Panel > Agents > Add New**.
- Add agent profiles, like **Jane Doe** and **John Doe**, with appropriate access permissions.

<p align="center">
<img src="https://i.imgur.com/ujpOdKM.png" alt="Jane Doe"/>
<img src="https://i.imgur.com/aKTJ01A.png" alt="John Doe"/>
</p>

---

### Step 6: Add Users

- Go to **Admin Panel > Users > Add New**.
- Add user profiles, such as **Ken User** and **Karen User**.

<p align="center">
<img src="https://i.imgur.com/vbPd3uK.png" alt="Ken User"/>
</p>

---

### Step 7: Configure SLA Plans

- Navigate to **Admin Panel > Manage > SLA**.
- Define SLA plans like:
  - **Sev-A**: 1 hour, 24/7.
  - **Sev-B**: 4 hours, 24/7.
  - **Sev-C**: 8 hours, business hours.

<p align="center">
<img src="https://i.imgur.com/6AAF3Ju.png" alt="Sev-A"/>
<img src="https://i.imgur.com/izcD74X.png" alt="Sev-B"/>
<img src="https://i.imgur.com/xKzdp7w.png" alt="Sev-C"/>
</p>

---

### Step 8: Define Help Topics

- Go to **Admin Panel > Manage > Help Topics**.
- Add help topics like:
  - **Business Critical Outage**
  - **Personal Computer Issues**
  - **Equipment Request**
  - **Password Reset**

<p align="center">
<img src="https://i.imgur.com/Xdhp63v.png" alt="Business Critical Outage"/>
<img src="https://i.imgur.com/3Y7k2o1.png" alt="Personal Computer Issues"/>
<img src="https://i.imgur.com/Z0eIGea.png" alt="Equipment Request"/>
<img src="https://i.imgur.com/ndOdtTZ.png" alt="Password Reset"/>
</p>

---

## Congratulations!

You have successfully configured osTicket post-installation. This configuration ensures that your help desk system is optimized for efficient ticket management. For further improvement, practice triaging and resolving tickets to enhance your help desk skills.
