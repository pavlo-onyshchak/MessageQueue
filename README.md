#Functional requirements
##1) Add message
###1.1)The messages should be added to the named queue.
###1.2)The queues should be isolated from each other(Unauthorized client can’t add/pop message to the queue)
##2) Pop message
##3)There are many isolated use cases
##4)For now,suppose that only one client can add/pop messages to the queue


#Non-functional requirements
##1) Fast(producer does not depend on customer response)
##2) Durable(Message send by producer should be always available,even in case of some error)
