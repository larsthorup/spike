# Config
 - title: Dilemma 1: Brad

# Description
When you started, you were told that Brad was one of your top performers, but that’s not what you have experienced so far.
You have no doubt that he is talented, but you feel that he is getting sloppy (resting on the laurels?)
and often find him being arrogant, especially towards the newer team members.

It’s now time for your appraisal dialogue with Brad. What approach shall you choose?

# Choice
 - title You tell him exactly how you feel, and try to appeal to him to improve his behavior
 - next: brad_a
# Variables
 - time: -1
 - engagement: -3
 - performance: -2

# Choice
 - title: You pick up 3 problematic situations from the past month where Brad’s behaviour have been a problem, and ask him to explain himself
 - next: brad_b
 # Variables
 - time: -1
 - engagement: -4
 - performance: -3

# Choice
 - title: You assume that there is an underlying problem that you should identify first. Therefore you start asking positive questions about what Brad likes/dislikes about his job – and ask into his ambitions for the future
 - next: brad_c
 # Variables
 - time: -1
 - engagement: +2
 - performance: +2

# Choice
 - title: You let him know that you are aware that there is a serious problem – but tell him that you are ready to help and coach him in weekly conversations for at least the coming 4 weeks
 - next: brad_d
 
 # Variables
 - time: -5
 - engagement: +0
 - performance: +0
