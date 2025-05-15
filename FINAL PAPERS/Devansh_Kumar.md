## Platemate  
Devansh Kumar, Spring 2025  

### Introduction

This project is informed by extensive observations across Southeast Asia, where many small, independently run restaurants operate with informal workflows. In these environments, efficiency is often achieved through routine rather than structure. Common practices include verbal order communication, handwritten tickets, or memory-based tracking. While these methods can function during off-peak hours, they frequently lead to confusion, delays, and missed orders when demand increases—ultimately affecting customer satisfaction and revenue.

These operational inefficiencies reflect a broader issue: limited access to practical, affordable digital tools in small and medium-sized food businesses. Popular platforms like Resy (2024) and Toast (2024), while feature-rich, are built for larger, tech-enabled restaurants and often assume the presence of trained staff and stable infrastructure. As a result, many smaller establishments are left underserved, unable to integrate such systems into their day-to-day operations.

Rather than overhauling established routines, Platemate seeks to support and enhance them—digitizing only the most critical operations in a way that aligns with the restaurant’s pace, physical constraints, and staffing realities.


### Purpose

The objective of this project is to design a Minimum Viable Product (MVP) that enables small and mid-sized restaurants to manage orders more efficiently. Core features include order entry (for both dine-in and takeout), kitchen ticket generation, and a lightweight admin dashboard. These components directly address common pain points such as miscommunication and a lack of operational visibility during peak hours.

The goal is to build a system that is functional, adaptable, and easy to adopt—one that enhances existing workflows without introducing unnecessary complexity. The MVP will serve as a foundation for future enhancements, including features like reservations, analytics, or inventory management based on user feedback and evolving needs.

### Target Audience

Platemate is designed for small to mid-sized restaurants that operate without robust digital infrastructure. These establishments often rely on paper tickets, verbal communication, or fragmented point-of-sale tools to manage orders and kitchen coordination. While such workflows may be familiar, they often break down during high-traffic periods, disrupting service quality.

Restaurant staff in these settings may be open to digital tools but hesitant to adopt complex platforms that require technical onboarding or recurring subscription fees. The need is for a streamlined, low-barrier system that improves order handling without disrupting daily routines. Whether serving a street food stall, café, or family-run diner, the system will be designed with simplicity and non-technical users in mind.

### Key Features

The MVP will focus on three key components: order tracking, kitchen ticketing, and an admin dashboard. The order tracking module will support both dine-in and takeout orders, with an initial emphasis on dine-in, given its prominence in smaller eateries. Orders will automatically generate digital kitchen tickets to ensure accuracy and consistent communication between front-of-house and kitchen staff. The admin dashboard will display active orders and basic metrics to help monitor operations.

Features such as table reservations, customer loyalty programs, and inventory tracking will be excluded in this phase. These functions are more relevant to larger-scale operations and are typically unnecessary in casual, fast-paced environments. The emphasis will remain on speed, clarity, and ease of use for staff with minimal technical experience.

### Strategy and Technology

The project will follow an agile and iterative development strategy. Key challenges—such as disorganized order entry, inefficient kitchen communication, and delayed service—will be addressed early through focused feature design. A PostgreSQL-backed system will be implemented to track and manage orders, with ongoing testing and feedback guiding refinements. Input from small restaurant operators will inform development priorities.

The backend will be built using Python with Flask or FastAPI for modular and efficient API development. PostgreSQL will be used for its relational performance and reliability. Hosting will be handled through platforms like Render or Railway, which streamline deployment and scaling.

The frontend will be a responsive web application built with HTML, CSS, and JavaScript. The interface will prioritize clarity and accessibility, designed for fast-paced environments and non-technical users. This initial release will form the basis for future iterations. The development process is outlined in Figure 1, which maps responsibilities and milestones using a swimlane diagram.

| ![](https://github.com/devanshk220304/Project-Management/blob/main/FINAL%20PAPERS/IS%20340%20-%20Workflow%20Diagram%20(2).png)|  
| :--: |  
| **Figure 1.** Swimlane diagram showing task responsibilities and timeline for Platemate’s MVP development. | 










