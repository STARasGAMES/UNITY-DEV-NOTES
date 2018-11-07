Just WTF... Spent 2 weeks on this issue...
UnityWebRequest.Post can't work with json request data, when Put, Get are work fine. 


So, this code doesn't work:
```c#
string requestData = "{ blablalba }"; //json
_unityWebRequest = UnityWebRequest.Post(URL, requestData);
_unityWebRequest.SetRequestHeader("Content-Type", "application/json"); // this line also very important, that was my issue for another 2 weeks :)
```
But this code work:
string requestData = "{ blablalba }"; //json
_unityWebRequest = UnityWebRequest.Put(URL, requestData); // change Post to Put
_unityWebRequest.method = "POST"; // manually set request method
_unityWebRequest.SetRequestHeader("Content-Type", "application/json");
