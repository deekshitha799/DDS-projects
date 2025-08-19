📄 README / Project Report Description
1. Executive Summary

The Hospital Patient Queue System is a simulation project designed to manage both emergency (critical) and regular patients efficiently. Using a priority queue for emergencies and a normal queue for regular patients, the system ensures fair and quick treatment. It also estimates waiting times, improving hospital workflow and patient satisfaction.

2. Project Overview

Problem Statement:
Hospitals often face challenges in managing patient inflow. Critical patients need immediate attention, while regular patients must wait in order. Without a proper queue system, delays and confusion occur.

Project Goals & Objectives:

Efficiently prioritize emergency cases.

Maintain order for regular patients.

Provide estimated waiting times.

Ensure transparency and fairness in patient management.

3. Features

🏥 Add Patient: Register patient with name, type (Emergency/Regular).

⚡ Priority Handling: Emergency patients are automatically moved ahead in the queue.

⏳ Estimated Wait Time: System calculates waiting time based on average consultation time.

📋 View Queue: Displays current patient list with priority order.

✅ Next Patient: Doctor can serve the next patient in the queue.

4. Advantages & Disadvantages

Advantages:

Emergency patients get immediate priority.

Transparent and systematic queue management.

Reduces patient frustration with wait-time estimates.

Simple, intuitive, and extendable.

Disadvantages:

Estimation accuracy depends on average consultation time.

Doesn’t yet handle multi-doctor scheduling.

5. How It Is Useful & Real-Life Applications

Usefulness:

Hospitals can streamline their patient flow.

Improves patient satisfaction and hospital efficiency.

Real-Life Applications:

Emergency wards for critical patient management.

Outpatient departments (OPD).

Small clinics to handle multiple patients fairly.

6. Project Methodology

Tools/Technologies: Python, Priority Queue (heapq), Normal Queue (deque).

Design Process: Identify patient types → Insert into appropriate queue → Merge queues with priority handling.

Testing: Simulated patient arrivals and treatments to validate correctness.

7. How to Run the Project

Steps to Run:

Install Python 3.x.

Save the file as hospital_queue.py.

Open terminal/command prompt in the file’s directory.

Run:

python hospital_queue.py


Use the menu to add patients, view the queue, and serve the next patient.

Requirements:

Python 3.x

Built-in heapq and collections (no external libraries needed).

8. Example Output
===== Hospital Patient Queue System =====
1. Add Patient
2. Show Queue
3. Serve Next Patient
4. Exit
Enter your choice (1-4): 1
Enter patient name: John
Enter type (E for Emergency, R for Regular): R
✅ Added regular patient: John

Enter your choice (1-4): 1
Enter patient name: Sarah
Enter type (E for Emergency, R for Regular): E
⚡ Emergency patient Sarah added with high priority!

Enter your choice (1-4): 2
📋 Current Queue:
1. Sarah (Emergency) - Wait: 0 min
2. John (Regular) - Wait: 10 min

Enter your choice (1-4): 3
👨‍⚕️ Now serving Sarah (Emergency)

9. Conclusion

The Hospital Patient Queue successfully manages both emergency and regular cases. It improves hospital efficiency and patient experience. Future upgrades may include multi-doctor support and dynamic wait-time adjustments.

🔟 Acknowledgement

Thanks to mentors, faculty, and peers for guidance and support in completing this project.
