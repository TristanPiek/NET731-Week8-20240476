# NET731-Week8-20240476
This Repository is for my Week 8 NET practical. 


Tristan Piek

20240476


## Budget Configuration

### Budget Details


Budget Name : Week8Budget 

Scope : Azure Subscription

Amount : $100 

Reset Period : Monthly 



### Alert Thresholds

| Threshold | Type |
|---|---|
| 80% | Actual Cost |
| 100% | Forecasted Cost |


### Why I Chose This

To keep track of the Azure spending and to prevent any shocks, I established a
monthly budget of one hundred dollars. The implementation of alert thresholds for
early warning messages was done in order to prevent the budget from going over its
limit.


## Cost Analysis and Optimization

### Resource Cost Review

The Cost Analysis tool was used to analyse expenditures by resource type, service and
resource group.


### Highest Cost Resource

The virtual machine resource was running throughout the practical exercises and
generated the highest cost.


### Optimization Performed

When not in use the VM was stopped and deallocated to minimise compute charges.


### Before and After Impact

Stopping the VM reduced the predicted monthly spend on computing and improved overall
budget efficiencies.


### Budgeted Amount For Each Month

After the optimisation process the expected monthly expense is around $46


### Recommendations

To begin, it is important to perform regular cost analysis and, if unused virtual
machines are discovered, to terminate them. You could also delete the storage and
public IP resources that are not being used.


## Reflection Questions


### 1. What surprised you most about Azure spending this week?

The rapid accumulation of expenses that occurs when virtual machines are left running
around the clock, even when they are not being utilised this came as a surprise to me.

### 2. How would cost management differ in a production environment used by a real
business?

When working in a production environment, you will require monitoring that is more
closely managed and policies that are automated for scaling and budgeting that is
more precise in order to prevent excessive expenditure while maintaining service
availability.

### 3. What additional Azure Cost Management features would you explore if you had
more time?

I would look at the possibilities of implementing suggestions from Azure Advisor,
reserved instances, tagging tactics and automated cost alerts to improve the
department's cost tracking.

