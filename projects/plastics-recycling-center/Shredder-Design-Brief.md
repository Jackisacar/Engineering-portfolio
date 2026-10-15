# Plastic Recycling Shredder Developement

 **Student: Jack Clouse**
 **Course: Engineering I**

 **Date:**
 10/15/26

 ## Motor Research & Developement
 I began by researching the motor and its controls, conditions, and eletronics. 

 ### Motor Specs
  The motor is a 1 HP 1725 RPM motor that can run at 115V or 230V; allowing for a direct connection to a standard wall socket.

  ### Motor challenge
  The motor has two primary challenges these being
    A. The motor has one speed setting (from the research we gatherd) *The speed can be changed by varying voltage but this will require a seperate part to regulate and control voltage
    B. The motor is 1725 RPM (We need around 20-40)

  ### Solutions
  We have a gear reducer —40:1— this means that we can reduce it down to roughly 42 RPM. I created the following equation for us or any other group to use, to caculate the ΔRPS This being 
```math
R_{driven} = ([R_{driver}/40^{-1}]/60)
```

 For the speed setting using a gear reducer also help control the speed though we still can only control the speed by varying the voltage & Current.


The next part of developement is designing the shredder

  ## Shredder Developement

  The shredder itself will be a one axle system, unlike things like paper shredders that have two blades that drive into each other to shred paper, we figured out that the most cost effiecent method is using one axle.

  ### How the Shredder works
  The shredder will have a set of moving blades, these blades will forcibly push plastic into small slits that are millimeters bigger then the blades, this will rip apart the plastic and will contiune until the plastic is cut enough to fit 
  within those milimeter gaps.

  ### Sizing
  For the total size of the machine we wint with a total length of 28" and a width of 22". The inner chamber where the shredder is is 10" by 18". 

  ### Designing the "shredding part"
  We found a open source file for parts of a Precious plastic machine. We assembled those parts in bamboo lab (To print off later for a visual prototype)

  Photo of a blade shown below
  
  <img width="400" height="350" alt="Screenshot 2026-10-15 122551" src="https://github.com/user-attachments/assets/3dbf4b36-55f4-48c6-9cc6-d5ba628c5deb" />


  ### The cart and structure
  We must also use have a structure to uphold the whole machine. We deisgned a lightweight sturcture that minimizes weight and space. It can be made out of wood and can easily be adjusted

  The "Cart" is how we plan to move the shredded plastic, this is going to be a bucket we can place in a load area, where plastic is dropped into the bucket to be put into the other systems.


  ## Closing thoughts

  We are close to being done with this side of the project, though we are still working on the acutal design, we are confident that whoever comes onto the project can contiune on and finish designing the shredder
