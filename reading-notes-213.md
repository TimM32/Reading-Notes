# Reading Notes Class 213 

- Why would a developer use local storage for a web application? Local storage allows developers to store and retrieve data in the browser. The data stored in local storage will not expire. This means the data will persist even if the tab or the browser window is closed.
- What information should not be stored in local storage? Given the potential vectors where malicious actors can access information on your browser's local storage, it is easy to see why sensitive information such as Personally Identifiable Information (PII), authentication tokens, user locations and API keys, etc., should never be stored in the local storage.
- Local storage can store what type of data? How would you convert it to that type before storing? The localStorage is an instance of the Storage type that allows you to store persistent data in the web browsers. The localStorage can store only strings. To store objects, you convert them to strings using the JSON. stringify() method.


## Additional Information
