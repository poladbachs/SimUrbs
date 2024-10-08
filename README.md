# City Economics Simulator

## Project Overview

**Simurbs** is a city economics simulator game developed to teach Urban Economics concepts to Economics students. The project combines strategy game elements with an educational platform, allowing users to simulate urban development and explore various economic parameters. 

The project features a dynamic front-end built with **VueJS**, and a robust back-end developed in **Java**, using the private **MetroBlocks 3D Engine Library** to handle the rendering of city blocks and buildings. 

Simurbs enables users to interact with a simulated city environment, modify the parameters of city blocks, and compare different simulation versions to study how individuals and economic activities are distributed across an urban setting.

This README highlights my contributions to **Simurbs**, focusing on the advanced front-end features and the urban economic models developed and integrated into the game.

> **Note**: This README serves as a showcase of the **Simurbs** project, which is hosted privately on GitLab. The source code is not publicly available due to the use of the proprietary **MetroBlocks 3D Engine Library**, which handles the rendering of city blocks and buildings. As a result, the project's functionality is demonstrated here through **GIFs** and **descriptions**.

## Demo

The application includes features such as a **Dynamic Minimap**, simulation **Comparison Mode**, and **Pagination** for managing a list of simulations. 

- **Main Menu and Simulation Page**

The GIF demonstrates the main menu of the **Simurbs** app, showcasing recent city simulations and basic statistics as well as the simulation page:

![simurbs_mm_compressed](https://github.com/user-attachments/assets/4279ec0d-f299-4fc4-a97a-9a3f5ae5ec8e)

- **Dynamic Minimap**

The **Dynamic Rotating Minimap** allows users to select and modify city blocks in real-time. As users adjust parameters like population or transportation costs, the minimap updates dynamically, reflecting changes instantly:

![simurbs_minimap_compressed](https://github.com/user-attachments/assets/0ce051ef-3599-4294-96d0-8a3c46bf3eef)

- **Simulation Comparison Mode and Modal Windows**

The **Simulation Comparison Mode** allows users to compare the current simulation with a selected previous version. Users can track changes in parameters like population, transportation costs, and income, with improvements highlighted in green and declines in red. **Modal windows** are used to edit parameters of the simulation and view comparisons without leaving the main interface, ensuring an intuitive user experience.

![simurbs_compare_compressed](https://github.com/user-attachments/assets/ea1b46a5-7be6-4f9c-a21d-9a0e79f03078)

- **Simulations Menu, Pagination, and Sorting**

The **Simulations Menu** allows users to manage and browse through multiple simulations efficiently. **Pagination** ensures smooth navigation between large sets of simulation data, while **Sorting** enables users to quickly arrange simulations by key parameters such as population and date added.

![simurbs_pages_compressed](https://github.com/user-attachments/assets/980f1d6f-265e-4732-a4fe-f80cba7c5ac2)

## Technologies Used

- **Frontend**:
  - **VueJS** for building dynamic user interfaces and handling state management.
  - **JavaScript** for logic and interactivity.
  - **Custom CSS** for additional styling and layout customization.
  
- **Backend**:
  - **Java** and **Spring Boot** for handling simulations and running urban economic models.
  - **MongoDB** for storing simulation data and historical records.
  
- **CI/CD**:
  - **GitLab CI/CD** for continuous integration and deployment pipelines.

## What I Did in This Project

In the **Simurbs** project, I was the **#1 contributor on the frontend** and the **#2 contributor on the backend**, among a team of 10 colleagues. Here is what I contributed:

### Frontend Contributions:

- **Dynamic Rotating Minimap**:
  - Implemented a synchronous minimap that updates in real-time as users interact with city blocks. Users can modify block parameters dynamically, and changes are reflected immediately on the minimap.

- **Simulation Comparison Mode**:
  - Developed the comparison feature that allows users to view and compare different simulations side-by-side. Implemented the UI to display differences between simulations in various parameters such as population, transportation costs, and income distribution.

- **Modal Windows for Simulation Edits**:
  - Designed and implemented modals for editing simulation parameters and comparing versions. These modals provide a user-friendly interface for making changes to simulations without leaving the main interface.

- **Pagination and Sorting**:
  - Implemented a paginated simulation list that allows users to navigate through previous simulations. Added sorting functionality by key economic parameters like population, date added, and transportation costs.

### Backend Contributions:

- **Urban Economics Models**:
  - Contributed to the implementation of core economic models that simulate the distribution of individuals and economic activities across the city. These models factor in over 10 parameters such as city edge, building height distribution, and land prices.

- **Performance Optimization**:
  - Reduced the loading time of the city simulation by 70% by optimizing data fetching processes and refining the accuracy of parameter calculations, including transportation costs and income distribution.

- **API Integration**:
  - Worked on the integration between the front-end and back-end, ensuring efficient data transfer between the VueJS frontend and the Spring Boot API.
