
# TODO List
- Overview of resource ownership, including stuff relating the rule of three.
- Special member generation after sections on movement
- Universal reference section
	- Section on perfect forwarding class template types via shadowing (can talk
	  about template expansion rules - show that conversion construction doesn't
	  occur in certain scenarios due to how the template is expanded)
- More petty stuff around special member generation
- Chapter on passing std::string around (or include in movement), talk about
  SSO, mention std::string_view, talk about how constraining a templated member
  function to a single type just to avoid writing an rvalue overload is bad
  practice, write about dislike of passing by-value just to move, etc.
