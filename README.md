# iBeaconScanner
Python3 iBeacn scanner

# Run the demo
sudo python3 iBeaconScanner.py

# Use the library
```
from iBeaconScanner import iBeaconScanner
...
scanner = iBeaconScanner(uuid="2f234454-cf6d-4a0f-adf2-f4911ba9ffa6", callback=myCallback)
print("Starting iBeaconScanner")
scanner.start()

done = False
while not done:
  try:
    time.sleep(1.0)
  except KeyboardInterrupt:
    done = True

scanner.stop()
```
