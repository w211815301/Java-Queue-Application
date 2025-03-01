package service;

import model.Task;
import java.util.LinkedList;
import java.util.Queue;

public class TaskQueueService {
    // In-memory queue to manage tasks
    private Queue<Task> queue = new LinkedList<>();

    // Enqueue a new task
    public void enqueue(Task task) {
        queue.add(task);
    }

    // List all tasks currently in the queue
    public Queue<Task> listTasks() {
        return queue;
    }

    // Dequeue (retrieve and remove) the first task from the queue
    public Task dequeue() {
        return queue.poll();
    }

    // Check if the queue is empty
    public boolean isEmpty() {
        return queue.isEmpty();
    }
}
