Just a link with explanations(tutorial): https://youtu.be/efOr9aWfRyY

Link Shell Extension:
https://www.youtube.com/redirect?q=http%3A%2F%2Fschinagl.priv.at%2Fnt%2Fhardlinkshellext%2Fhardlinkshellext.html&redir_token=rqkNUy6YGWmRnXYGBAilm5ZIPsV8MTU0ODMyNDYxNEAxNTQ4MjM4MjE0&v=efOr9aWfRyY&event=video_description

I use this method not only for platform switching. I had big project that need to work on Google VR and Oculus VR. It's the same application but with some specifics for each platform. So I decided to store CORE code base(ServerCommunication and GameSystem) in Google VR project, and copy this CORE code base to Oculus project through Link Shell's junk folders. And use definitions to keep track of current platform in scripts.
