# gid-remove-concept

A data component to remove concept

    <gid-remove-concept user='1' conceptId='10002'>
    </<gid-remove-concept>
    
The properties 'conceptId' and 'user' are mandatory.

API endpoint:

    DELETE /concepts/{id}

Input:

- Concept Id
- User Id
	
Output:

      {
        "message" : "Concept removed successfully"
      }
