Just a link with explanations(tutorial): https://youtu.be/efOr9aWfRyY

Link Shell Extension:
http://schinagl.priv.at/nt/hardlinkshellext/hardlinkshellext.html

I use this method not only for platform switching. I had big project that need to work on Google VR and Oculus VR. It's the same application but with some specifics for each platform. So I decided to store CORE code base(ServerCommunication and GameSystem) in Google VR project, and copy this CORE code base to Oculus project through Link Shell's junk folders. And use definitions to keep track of current platform in scripts.
