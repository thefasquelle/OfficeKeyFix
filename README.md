# OfficeKeyFix

Unbinds the Office Key (Shift+Control+Alt+Win) related shortcuts, allowing you to use Office+W in other applications.

Open the solution with visual studio (you need the C++ workoad) and build the  Release configuration. 
Then place the porogram in `%APPDATA%\Roaming\Microsoft\Windows\Start Menu\Programs\Startup` so it will run on startup.

# Changes from acook's repositiory

- Ready to build Viual Studio solution
- Also unbind the office key alone (opens web browser to office page)
- Exit with code 0 instead of 1 so terminal does not stay opened 

# See Also

- https://github.com/jorystewart/OfficeKeyFix
