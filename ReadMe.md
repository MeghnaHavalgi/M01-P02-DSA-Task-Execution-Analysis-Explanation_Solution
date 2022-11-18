Task Execution Analysis

Code Structure
    1. We have LinkedList.py file which is responsible for defining Node and LinkdList classes. 
    2. Node class is responsible for defining data point for storing data for the task. We store the following data in the task node:
        a. Task ID
        b. Start Time
        c. End Time

    3. LinkedList is responsible for initialising linked list for the tasks created using config.py file. In this various as following are implemented:
        a. print_linked_list : Printing Linked List elements
        b. insert_node : Inserting node in the linked list either in beginning or at the end.
        c. print_in_reverse : Printing the linked list in reverse order

    4. We have Aggregate.py which is responsible for following operations on the linked list:
        a. get_minimised_timed_task : This will provide the task details having minimum task time aming all the tasks in the linked list.
        b. get_maximised_time_task : This will provide the task details having maximum task time aming all the tasks in the linked list.
        c. get_average_time_of_all_tasks : This will calculate the average of all task execution times.

    5. We have config.py which will craete the linked list from the provided csv file

Steps to run the code : python3 main.py