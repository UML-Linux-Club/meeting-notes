# [UMass Lowell Linux Club Meeting Notes (Fall 2021)](https://www.uml.edu/myuml/Submissions/2021/2021-09-03-12-39-30-UML-Linux-Club-Fall-meetings.aspx)
Notes from meetings held during the [academic semester](https://www.uml.edu/myuml/Submissions/2021/2021-09-03-12-39-30-UML-Linux-Club-Fall-meetings.aspx).

  1. **03Sep2021 Zoom meeting; web link *and phone number* available at the `uml-linux` Google group**
     + Continue to learn how to develop [MOOSE](https://mooseframework.inl.gov/) apps
     + Issues installing MOOSE from [last semester](https://github.com/UML-Linux-Club/moose-info).
      - Download and install the Cubit free educational license binary.
     + Focus on geometry and meshing for more elaborate problems
     + Use the geometry and mesh generation package [Coreform Cubit](https://coreform.com/products/coreform-cubit/) 
     + Transfer data to MOOSE through a MOOSE `input.hit` file

  2. **10Sep2021 Zoom meeting; web link *and phone number* available at the `uml-linux` Google group**
     + Creating simple geometry and meshing as an alternate to MOOSE meshing for [Engy-5310 course](https://github.com/dpploy/engy-5310).
     + A separate `README.md` file created for geometry and meshing with Coreform Cubit created.
    + Files will be eventually be uploaded in the course repo.

  3. **17Sep2021 Zoom meeting; web link *and phone number* available at the `uml-linux` Google group**
     + More issues with Coreform-Cubit education license install. Not working with Linux.
     + Continue to work on meshing examples for Engy-5310.

  3. **24Sep2021 Zoom meeting; web link *and phone number* available at the `uml-linux` Google group**
     + Meeting notes not available.

  3. **01Oct2021 Zoom meeting; web link *and phone number* available at the `uml-linux` Google group**
     + Meeting notes not available.

  3. **08Oct2021 Zoom meeting; web link *and phone number* available at the `uml-linux` Google group**
     + Testing 2D simple CUBIT meshes for course notebooks.
     + Creating a bi-quadratic `quad9` mesh in CUBIT for MOOSE usage. For now use a CUBIT command line to create a block of elements with `quad9` type. Save mesh in `exodus` format. More on this later.

  3. **15Oct2021 Zoom meeting; web link *and phone number* available at the `uml-linux` Google group**
     + Apparently element order is changed via the command prompt, *e.g*:
      - block 1 surface 2
      - block 1 element type QUAD9
     + Delete the block later if needed for other changes
     + Element order can be changed by creating a block either at the command line or the UI.
      - Then select the Block on the project tree and the properties will appear at the bottom left pallete
      - On the `Element Type` entry, select the element type.
      - 2D elements tested with MOOSE/CUBIT: tri3, tri7, quad4, and quad9

  3. **29Oct2021 Zoom meeting; web link *and phone number* available at the `uml-linux` Google group**
     + General hands-on work
     + Python programming on finite element basis functions
