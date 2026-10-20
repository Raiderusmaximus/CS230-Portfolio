# Joseph Villicano: CS 230 Software Design Portfolio

## Module Eight Journal Reflection

### 1. The client and their software requirements

The client was The Gaming Room, which wanted a software design for its game, Draw It or Lose It. The design document covers the system architecture, the operating platform, storage and memory management, distributed systems and networks, and security. Across Projects One through Three, the goal was to design software that the client can expand to other computing environments while keeping user information protected.

### 2. What I did particularly well

I kept the documentation organized around the client's needs, so each section answers a specific question the client would ask. In the Recommendations section I tied each technical choice back to a requirement, such as choosing a managed cloud database to support growth and using HTTPS and a firewall to protect user information between platforms.

### 3. What helped when developing the code

Working through the design document before writing code made the requirements clearer. Describing how the game would communicate across platforms, which components depended on each other, and where data would be stored helped me see the structure before I built it. That made it easier to explain my decisions to a client and to my development team.

### 4. What I would revise

If I revised one part, it would be the Recommendations section. I would add a clearer cost comparison between the operating platform options so the client can see the tradeoffs in dollars as well as in capability. I would also state the assumptions behind the recommendation more directly, so a reader knows which conditions would change the choice.

### 5. Interpreting the user's needs

I read the client's requirements as both functional needs, such as the game running across platforms, and quality needs, such as reliable service and protection of player information. I translated those into design decisions, including the managed database, the client-server structure, and the security controls. Considering the user's needs is important because software that works technically but frustrates or exposes its players will not be used, and the design has to protect the people who depend on it.

### 6. My approach to designing software

I start with the client's requirements and the people who will use the software, then identify the main components and how they connect. I document the reasons for each decision, consider the dependencies between components, and check the design against the requirements. In future projects I would use the same approach: define the requirements first, sketch the architecture, document the tradeoffs, and review the design with the client or team before coding.
