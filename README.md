# Simurbs: City Economics Simulation Game

## Project Overview

**Simurbs** is a city economics simulation game developed to teach Urban Economics concepts to Economics students. The project combines strategy game elements with an educational platform, allowing users to simulate urban development and explore various economic parameters. 

The project features a dynamic front-end built with **VueJS**, and a robust back-end developed in **Java**, using the **MetroBlocks 3D Engine Library** to handle the rendering of city blocks and buildings. 

Simurbs enables users to interact with a simulated city environment, modify the parameters of city blocks, and compare different simulation versions to study how individuals and economic activities are distributed across an urban setting.

> **Note**: This README serves as a showcase of the **Simurbs** project, which is hosted privately on GitLab. The source code is not publicly available due to the use of the proprietary **MetroBlocks 3D Engine Library**, which handles the rendering of city blocks and buildings. As a result, the project's functionality is demonstrated here through **GIFs** and **descriptions**.

> This README highlights my contributions to **Simurbs**, focusing on the advanced front-end features and the urban economic models integrated into the game.

## Demo

The application includes features such as a dynamic minimap, simulation comparison mode, and pagination for managing a list of simulations. The GIF below demonstrates the main menu of the **Simurbs** app, showcasing interactive recent city simulations and basic statistics:




## Features

- **Dynamic Rotating Minimap**: Users can interact with a live-updating minimap to select specific city blocks and modify their parameters.
- **Simulation Comparison Mode**: Compare the current city simulation with older versions to understand changes in parameters such as population, transportation costs, and income.
- **Modal Windows for Editing**: Multiple modals allow for seamless editing of simulations, parameter updates, and viewing comparisons.
- **Pagination for Simulation Management**: Efficiently navigate through a list of past simulations, which can be sorted by parameters such as population, date added, and more.
- **Sorting and Filtering**: The simulations list can be sorted dynamically by key parameters, allowing users to analyze data efficiently.

## Technologies Used

- **Frontend**:
  - **VueJS** for building dynamic user interfaces and handling state management.
  - **JavaScript** for logic and interactivity.
  - **Custom CSS** for additional styling and layout customization.
  
- **Backend**:
  - **Java** and **Spring Boot** for handling simulations and running urban economic models.
  - **MongoDB** for storing simulation data and historical records.
  - **Docker** and **Kubernetes** for containerization and deployment.
  
- **CI/CD**:
  - **GitLab CI/CD** for continuous integration and deployment pipelines.

## What I Did in This Project

In the **Simurbs** project, I was heavily involved in both the front-end and back-end development, with a particular focus on front-end functionality. Here is what I contributed:

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
