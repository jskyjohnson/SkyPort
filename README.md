# SkyPort

SkyPort: A modular website framework by Sky, blending web dev, art, and more with frontend excellence. Powered by Scala and SolidJS, it's a customizable platform for tech enthusiasts.

**SkyPort**: A dynamic and modular personal website framework, meticulously crafted to showcase the multifaceted passions of its creator, Sky. From web development and machine learning to art and astronomy, SkyPort seamlessly integrates a plethora of interests under one digital roof. With its emphasis on frontend excellence and user-centricity, powered by Scala and SolidJS, SkyPort serves as a testament to Sky's diverse talents while offering a customizable platform for tech enthusiasts.

## **Intentions & Goals**

- **Personal Showcase**: A platform to fluently display Sky's wide-ranging interests and works.
- **Reusability**: A modular design allowing others to set up and customize their personal spaces swiftly.
- **Frontend Excellence**: A commitment to providing intuitive, responsive, and engaging user interfaces.
- **Ease of Onboarding & Documentation**: Ensuring a straightforward setup process, backed by thorough documentation.

## **Project Structure (Monorepo)**

```
/SkyPort
|-- /backend
| |-- /models
| |-- /controllers
| |-- /services
| |-- /App.scala
| ...
|
|-- /frontend
| |-- /components
| |-- /pages
| |-- /assets
| |-- /styles
| ...
|
|-- /scripts
|-- /config
|-- /docker
|-- README.md
|-- .gitignore
```

## **Getting Started**

### Prerequisites

- Scala and SBT installed (version to be specified)
- Node.js & npm installed (for the SolidJS frontend)
- PostgreSQL set up and running

### Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/SkyPort.git
    ```

2. Navigate to the backend directory and build the Scala project:
    ```bash
    cd backend && sbt compile
    ```

3. Navigate to the frontend directory and install required npm packages:
    ```bash
    cd frontend && npm install
    ```

4. Configure necessary environment variables in the `/config` directory (details to be added later).

5. Run necessary setup scripts from the `/scripts` directory (details to be provided as the project progresses).

### Development

To start the development server for both backend and frontend (more detailed instructions will be added as the project progresses):

```bash
# In the backend directory
sbt run

# In the frontend directory
npm run dev
```

## **Contribution & Feedback**

While SkyPort is primarily a personal endeavor, constructive feedback, issue reporting, and contributions are always welcome. If you decide to contribute, please adhere to the provided guidelines when making a pull request.

## **Roadmap**

### **Phase 1: Foundation & Basic Functionality**

- **SolidJS Frontend**:
  - Initial responsive design to showcase portfolio items.
  - Visual coding art displays.
  - Basic routing setup.
- **Scala  Backend**:
  - Setup basic server.
  - Establish connection with PostgreSQL.
  - GraphQL schema and resolver setup.
- **Portfolio Features**:
  - Display sections for web development, machine learning, art, astronomy, and other maker space interests.
  - Upload and manage multiple file types (images, audio, code snippets).
- **Dockerization & Local Hosting**:
  - Set up Dockerfile for easy deployment.
  - Local hosting setup with Nginx reverse proxy.

### **Phase 2: Documentation & User Support**

- **Full Wiki & Documentation**:
  - Comprehensive guides on each feature and module.
  - Best practices for customization and extension.
  - Troubleshooting and FAQ sections.
- **Setup & User Guides**:
  - Detailed steps for first-time setup.
  - Video tutorials or webinars for complex integrations.
  - User guides for navigating and using the website once live.

### **Phase 3: Expansion & Enrichment**

- **E-commerce Integration**:
  - Product listing and management.
  - Shopping cart functionality.
  - Secure payment gateway integration.
- **Blog & Social Integration**:
  - Live blog with categories and tags.
  - Comment system integration.
  - Live streaming schedule display.
  - Social media feed and link integrations.
- **Admin Portal**:
  - Content management system (CMS) to live update website content.
  - Analytics dashboard.
- **Monorepo Structuring & DevOps**:
  - Dividing project into logical sub-modules.
  - CI/CD pipeline setup.

### **Phase 4: Refinement & Scale**

- **Advanced Features & Enhancements**:
  - Advanced search functionalities.
  - Personalized user experiences.
  - Subscription and
