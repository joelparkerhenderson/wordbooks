# Activity diagram

An activity diagram is a type of behavioral diagram in software engineering that describes the flow of activities or actions within a system or process. It is a graphical representation of the steps or actions that take place in a workflow or business process, and can be used to model complex systems or business processes.

An activity diagram consists of the following elements:

* Activities: An activity is a task or action that takes place in the system or process. It is represented as a rectangle with rounded corners, and the name of the activity is written inside the rectangle. For example, in a banking system, an activity could be "Withdraw Money".

* Transitions: A transition is a connection between activities that shows the flow of control from one activity to another. It is represented as an arrow, and the label on the arrow describes the condition or event that triggers the transition. For example, in a banking system, a transition could be "Verify Account" that occurs before the "Withdraw Money" activity.

* Decisions: A decision is a point in the process where the flow of control splits into multiple paths based on a condition or event. It is represented as a diamond with arrows indicating the possible paths. For example, in a banking system, a decision could be "Has Sufficient Balance?" that leads to two paths: "Yes" and "No".

* Forks and Joins: A fork is a point in the process where the flow of control splits into multiple parallel paths. It is represented as a bar with multiple arrows indicating the paths. A join is a point in the process where the parallel paths converge back into a single path. It is represented as a bar with multiple arrows merging into a single arrow. For example, in a banking system, a fork could be used to handle multiple withdrawal requests at the same time, and a join could be used to synchronize the results of the withdrawal requests.

* Swimlanes: A swimlane is a visual element used to indicate the participation of different actors or departments in a process. It is represented as a horizontal or vertical rectangle with the name of the actor or department written inside. For example, in a banking system, a swimlane could be used to indicate the roles of the customer and the bank employee in the withdrawal process.

Activity diagrams are useful for modeling complex systems or business processes and for analyzing the flow of activities within those systems or processes. They are also useful for communicating the design of a system or process to stakeholders and for documenting the behavior of a system for future reference.