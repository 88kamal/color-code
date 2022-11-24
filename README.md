# Hello Every One
I am KAMAL NAYAN UPADHYAY


***** HOW TO USE THIS NPM PACKAGE *****

STEP 1: import { Log } from 'colorkamal'

STEP 2: import { useEffect } from 'react';

STEP 3: Implement in UseEffect Hook
 useEffect(() => {
    Log.success("Signup Successfully")
    Log.danger("Signup failed")
    Log.success("You See")
  }, []);

STEP 4: Output Step
=> Signup Successfully {color:green}
=> Signup failed       {color:red}
=> You See             {color:blue}