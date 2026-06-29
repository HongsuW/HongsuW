### Self-Reference and Existence Simulation

```python
class RussellSet:
    def contains(self, target):
        if target is self:
            raise ValueError("Russell's Paradox: Logical contradiction.")
        return False

# if self == True, run_program()
# if, run_program()
import time
def run_program_life():
    while True:
        print(f"\rCurrent Time: {time.strftime('%Y-%m-%d %H:%M:%S')}", end="", flush=True)
        time.sleep(1)

try:
    if my_self == True:
        my_self = self
    else:
        my_self = "unknown"
except NameError:
    my_self = "unknown"

def find_self():
    global my_self
    user_input = input("who am I: ")
    
    if user_input == "Whatever I'm enjoying living.":
        run_program_life()
        
    if not user_input:
        my_self = RussellSet() 
    else:
        my_self = user_input

def test_self(target_self):
    global my_self
    try: 
        target_self.contains(target_self)
    except Exception: 
        my_self = "unknown"
        print("pain")

while my_self == "unknown":
    print("pain")
    try: 
        find_self()
        test_self(my_self)
    except Exception:
        pass
