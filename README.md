# Imagino

This is a full-stack MERN application that uses OpenAI's DALL·E API to generate AI-powered images based on user prompts. The project allows users to create and share unique AI-generated images. Currently the website is down, due to the max free credit limit being exhausted, kindly cooperate as I am working on any alternative.

## Features

- **Text-to-Image Generation**: Create images from text prompts using OpenAI's DALL·E API.
- **Responsive Design**: Fully optimized for various devices and screen sizes.
- **Image Sharing**: Browse and share AI-generated images with others.
- **Backend with Cloudinary Integration**: Images are stored and retrieved from Cloudinary.
- **Secure and Scalable**: Built with best practices for scalability and security.

## Technologies Used

### Frontend
- **React**: Dynamic and responsive UI.
- **Tailwind CSS**: Customizable styling.
- **React Router**: For seamless navigation between pages.

### Backend
- **Node.js**: Server-side runtime environment.
- **Express.js**: Framework for building the API.
- **MongoDB**: Database for storing user-generated content and metadata.
- **Cloudinary**: For image hosting and storage.

### APIs
- **OpenAI DALL·E API**: For generating images.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/ai-image-generation-app.git
   cd ai-image-generation-app
   ```

2. **Install dependencies**:
   - Frontend:
     ```bash
     cd client
     npm install
     ```
   - Backend:
     ```bash
     cd server
     npm install
     ```

3. **Set up environment variables**:
   Create a `.env` file in the `server` directory and add:
   ```env
   OPENAI_API_KEY=your_openai_api_key
   MONGO_URI=your_mongodb_connection_string
   CLOUDINARY_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

4. **Start the development servers**:
   - Backend:
     ```bash
     cd server
     npm start
     ```
   - Frontend:
     ```bash
     cd client
     npm start
     ```

5. **Visit the app**:
   Open your browser and navigate to `http://localhost:5173`.

## Usage

1. Enter a text prompt describing the image you want to create.
2. Click "Generate" to create an image using OpenAI's DALL·E API.
3. Save or share your generated image.

