# AWS Mini Project 1
Hosting a static website on Amazon S3

+----------------+     1. Create Bucket     +-------------------+
|                | -----------------------> |                   |
|  AWS Console   |                          |   Amazon S3       |
|                | <----------------------- |    Bucket         |
+----------------+     2. Configure ACLs    +-------------------+
        |                                            ^
        |                                            |
        | 3. Upload Files                            |
        |                                            |
        v                                            |
+----------------+                                   |
|   Web Files    |                                   |
|  - index.html  |                                   |
|  - style.css   |                                   |
|  - script.js   |                                   |
|  - images      |                                   |
+----------------+                                   |
                                                     |
+----------------+     4. Access Web Page    +-------+-------+
|                | ----------------------->  |               |
|   Web Browser  |                          |  Static       |
|                | <-----------------------  |  Website      |
+----------------+                          |               |
                                            +---------------+
