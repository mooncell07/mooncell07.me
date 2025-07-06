@5

# 0: I think it's time to change a few stuff in mayuri.
# 1: Is it regarding the interface?
# 0: Yeah.
# 1: I understand, you've been ranting about it since the beginning.
# 0: Yeah, I never really liked the design, it felt hacky.
# 0: Apart from that, from technical standpoint, the state management in this approach is really limiting.
# 1: I am assuming you're going to switch to traits based approach now?
# 0: Yes.
# 1: It has its own issues too you know?
# 1: I remember you talking about how this approach introduces alot of branching in the handler for redirection of data.
# 0: Yeah precisely why I didn't switch to it earlier.
# 1: So why now?
# 0: The argument still stands but I don't think it's that big of a matter as I was thinking initially.
# 0: I soon realised that my field of vision was pretty narrow, what i building was more of a design meant for command handlers, not general purpose communication libraries.
# 0: The truth is, generally speaking, nobody expects command handling from libs meant for communication.
# 1: So, what are you gonna do about it? You're basically deligating the work to users of your lib.
# 0: This is far out of scope for such a thing.
# 0: Not everyone have a use for command handlers.
# 0: Hell my implementation wasnt a pure command handler too, it had a dispatcher which would broadcast content to multiple handlers.
# 1: You know what, it does make sense. This way users can freely broadcast and handle events. 
# 0: Yep!

 