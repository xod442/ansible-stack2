# ansible-stack2
three tier web application role out


            +-------------+
            |             |
            |   Control   |
            |             |
            +-------------+ 
                   |
                   +-----------------------------------------------------------+
                   |                    |                                      |
            +-------------+        +-------------+  +-------------+        +-------------+
            |loadbalancer |        |   app01     |  |   app02     |        |   database  |
            |   lb01      |        | webserver   |  | webserver   |        |     db01    |
            +-------------+        +-------------+  +-------------+        +-------------+ 

This set of ansible playbooks provision the three tier application and also includes the test functionality 
                                   