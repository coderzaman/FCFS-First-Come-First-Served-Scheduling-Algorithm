

---
# FCFS (First-Come, First-Served) Scheduling Algorithm

This Bash script implements the First-Come, First-Served (FCFS) scheduling algorithm, a simple non-preemptive algorithm where processes are executed in the order they arrive.

## Usage

1. Ensure you have Bash installed on your system.

2. Clone the repository:

   ```bash
   git clone https://github.com/coderzaman/FCFS-First-Come-First-Served-Scheduling-Algorithm.git
   ```

3. Navigate to the project directory:

   ```bash
   cd fcfs-scheduling
   ```

4. Make the script executable:

   ```bash
   chmod +x fcfs.sh
   ```

5. Run the script:

   ```bash
   ./fcfs.sh
   ```

6. Follow the on-screen prompts to input the number of processes, arrival times, and burst times.

## Input Details

- **Number of Processes (number):** The total number of processes in the system.

- **Process Names (p):** An array representing process names (e.g., P1, P2).

- **Arrival Times (a):** An array representing arrival times for each process.

- **Burst Times (b):** An array representing burst times for each process.

## Arrival Time Sorting (FCFS Specific)

Processes are sorted based on their arrival times in ascending order. In case of a tie in arrival times, the original order is preserved.

## Output

The script outputs the sorted process names, arrival times, and burst times, along with a detailed table displaying the completion time, turnaround time, and waiting time for each process.

## Average Metrics

The script calculates and displays average completion time, average waiting time, and average turnaround time for all processes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

[Aktaruzzaman]

Feel free to contribute, report issues, or provide feedback.

Happy coding! 🚀

