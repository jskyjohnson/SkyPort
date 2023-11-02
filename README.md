# SkyPort
SkyPort: A modular website framework by Sky, blending web dev, art, and more with frontend excellence. Powered by Go and SolidJS, it's a customizable platform for tech enthusiasts.

**SkyPort**: A dynamic and modular personal website framework, meticulously crafted to showcase the multifaceted passions of its creator, Sky. From web development and machine learning to art and astronomy, SkyPort seamlessly integrates a plethora of interests under one digital roof. With its emphasis on frontend excellence and user-centricity, powered by Go and SolidJS, SkyPort serves as a testament to Sky's diverse talents while offering a customizable platform for tech enthusiasts.

## **Intentions & Goals**

- **Personal Showcase**: A platform to fluently display Sky's wide-ranging interests and works.
  
- **Reusability**: A modular design allowing others to set up and customize their personal spaces swiftly.

- **Frontend Excellence**: A commitment to providing intuitive, responsive, and engaging user interfaces.
  
- **Ease of Onboarding & Documentation**: Ensuring a straightforward setup process, backed by thorough documentation.

## **Project Structure (Monorepo)**

```
/SkyPort
|-- /backend
|   |-- /models
|   |-- /resolvers
|   |-- /middlewares
|   |-- main.go
|   ...
|
|-- /frontend
|   |-- /components
|   |-- /pages
|   |-- /assets
|   |-- /styles
|   ...
|
|-- /scripts
|-- /config
|-- /docker
|-- README.md
|-- .gitignore
...
```

## **Getting Started**

### Prerequisites

- Go installed (vX.XX)
- Node.js & npm installed (for the SolidJS frontend)
- PostgreSQL set up and running

### Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/SkyPort.git
    ```

2. Navigate to the backend directory and install the necessary Go packages (details to be provided as the project progresses).

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
go run main.go

# In the frontend directory
npm run dev
```

## **Contribution & Feedback**

While SkyPort is primarily a personal endeavor, constructive feedback, issue reporting, and contributions are always welcome. If you decide to contribute, please adhere to the provided guidelines when making a pull request.

## **Roadmap**

A list of planned features, improvements, and milestones will be periodically updated here.

## **Commitment**

The journey of SkyPort is in its early stages. It aims not just to be a personal expression but to also provide a robust, adaptable, and delightful platform for many. Your support, feedback, and contributions will be invaluable on this journey.
