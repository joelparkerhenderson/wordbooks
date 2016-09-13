# PERT: program evaluation and review technique

Thanks to https://en.wikipedia.org/wiki/Program_evaluation_and_review_technique

* PERT event: a point that marks the start or completion of one or more activities. It consumes no time and uses no resources. When it marks the completion of one or more activities, it is not "reached" (does not occur) until all of the activities leading to that event have been completed.

* predecessor event: an event that immediately precedes some other event without any other events intervening. An event can have multiple predecessor events and can be the predecessor of multiple events.

* successor event: an event that immediately follows some other event without any other intervening events. An event can have multiple successor events and can be the successor of multiple events.

* PERT activity: the actual performance of a task which consumes time and requires resources (such as labor, materials, space, machinery). It can be understood as representing the time, effort, and resources required to move from one event to another. A PERT activity cannot be performed until the predecessor event has occurred.

* PERT sub-activity: a PERT activity can be further decomposed into a set of sub-activities. For example, activity A1 can be decomposed into A1.1, A1.2 and A1.3. Sub-activities have all the properties of activities; in particular, a sub-activity has predecessor or successor events just like an activity. A sub-activity can be decomposed again into finer-grained sub-activities.

* optimistic time: the minimum possible time required to accomplish an activity (o) or a path (O), assuming everything proceeds better than is normally expected

* pessimistic time: the maximum possible time required to accomplish an activity (p) or a path (P), assuming everything goes wrong (but excluding major catastrophes).

* most likely time: the best estimate of the time required to accomplish an activity (m) or a path (M), assuming everything proceeds as normal.

* expected time: the best estimate of the time required to accomplish an activity (te) or a path (TE), accounting for the fact that things don't always proceed as normal (the implication being that the expected time is the average time the task would require if the task were repeated on a number of occasions over an extended period of time).

* standard deviation of time : the variability of the time for accomplishing an activity (σte) or a path (σTE)

* float or slack: a measure of the excess time and resources available to complete a task. It is the amount of time that a project task can be delayed without causing a delay in any subsequent tasks (free float) or the whole project (total float). Positive slack would indicate ahead of schedule; negative slack would indicate behind schedule; and zero slack would indicate on schedule.

* critical path: the longest possible continuous pathway taken from the initial event to the terminal event. It determines the total calendar time required for the project; and, therefore, any time delays along the critical path will delay the reaching of the terminal event by at least the same amount.

* critical activity: An activity that has total float equal to zero. An activity with zero float is not necessarily on the critical path since its path may not be the longest.

* lead time: the time by which a predecessor event must be completed in order to allow sufficient time for the activities that must elapse before a specific PERT event reaches completion.

* lag time: the earliest time by which a successor event can follow a specific PERT event.

* fast tracking: performing more critical activities in parallel

* crashing critical path: Shortening duration of critical activities