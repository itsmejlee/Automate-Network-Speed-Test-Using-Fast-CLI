## Automate Network Speed Test Using Fast CLI

<img width="261" height="104" alt="image" src="https://github.com/user-attachments/assets/3e03f42f-8a52-4b30-8f8a-6e8d9a1141fc" />


**Overview**

As part of my daily taks, I am required to report the bandwidth of three ISPs every hour. Doing this task manually is time-consuming, especially while handling other tasks.

To improve efficiency, I created an automated solution that generates hourly network speed reports using Fast CLI. This allows consistent monitoring with minimal manual intervention.


> **Note**:
> _Although Speedtest CLI by Ookla is available, it is primarily intended for personal or educational use. To avoid potential licensing issues, this project uses Fast CLI instead._

**Technologies Used:**

- Fast CLI – Internet speed testing tool powered by Fast.com 
- PowerShell – Script automation
- Task Scheduler – Schedule hourly execution
- JSON – Structured data handling
- Node.js – Required to run Fast CLI

**How It Works**

- Fast CLI runs via a PowerShell script
- The script captures the speed test result in JSON format
- Data is logged or stored for reporting
- Task Scheduler runs the script every hour automatically

**Purpose**
- Automate repetitive ISP bandwidth monitoring
- Reduce manual workload
- Ensure consistent and timely reporting
