# Database Schema

`Student(__studentID__, username, calvinEmail)`  

`StudentCommunity(__studentID__, __communityID__)`  

`Community(__communityID__, communityName, description, location)`  

`Post(__postID__, title, author, communityID, upvotes, timePosted, type)`  

`Reply(__answerID__, author, questionID, upvotes, content, timeAnswered)`  

`Label(__Name__)`  

`PostLabel(__questionID__, __labelName__)`  
