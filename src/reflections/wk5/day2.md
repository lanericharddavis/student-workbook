# DAY2 | USING AN ORM TO INTERACT WITH A DATABASE

## What are the three types of relationships?
1) One-To-One
2) One-To-Many
3) Many-To-Many
## What are the benefits of the traditional linking of relationships instead of Embedding
Embedding attaches the child elements directly to the parent.  This is fine with smaller applications that won't run the risk of having lots of child elements attached.  Embedding allows for the application to collect the information more efficiently cause it only has to run through one document to gather the data.  However, if there is a large number of child elements, there could be an issue with maximum document sizing.

Traditional linking doesn't add the child element directly to the parent thus you do not run the risk of document sizing limitations.  Linking is preferred for larger scale one-to-many relationships.  Instead of embedding the child directly to the parent, you give the parent an ID number and every child element that is linked to that parent will have that parents ID attached to it, linking the two together.

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
There are a few different ways you can manage a many-to-many relationship: Two way embedding, one way embedding, and third collection embedding.
Ultimately, it boils down to how much data you plan on using and how you are planning to use it.  The most effective of managing a many-to-many relationship is using third collection embedding.  This is where you will have three models for the data.  One for a specific object, like a subscriber of video streaming service, the second for the movie, and the third for a particular way of managing those first two, say like favorite movies.

## Afternoon Challenge | GregsList-Server
https://lanericharddavis.github.io/spring21-gregslist-server/