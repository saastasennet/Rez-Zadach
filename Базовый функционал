#include "Task.h"
#include <vector>
#include <iostream>
using namespace std;

class Project {
public:
    void addTask(const Task& task) {
        tasks.push_back(task);
    }
    
    void listTasks() {
        for (const auto& task : tasks) {
            cout << "- " << task.getDescription() << "\n";
        }
    }
    
private:
    vector<Task> tasks;
};
