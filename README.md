# PriorityHandler

## How to use

You can simply creat a new list using PriorityList wrapper:

    List<PriorityItem<string>> priority_list = new List<PriorityItem<string>>();

Then by the help of PriorityManager class insert, swap and do a lot of priority related stuff like this:

    PriorityManager<PriorityItem<string>> priority_manager = new PriorityManager<PriorityItem<string>>();
    priority_manager.PriorityInsert(priority_list, line, new PriorityItem<string>((++count).ToString()));
    priority_manager.Swap(priority_list, indexA, indexB);