# AI Travel Assistant

An intelligent travel planning application powered by Groq AI that helps you create personalized travel itineraries, packing lists, and budget plans for your next adventure.

## Features

### 🗺️ Intelligent Itinerary Generator
- AI-powered daily activity recommendations based on your destination, travel style, and interests
- Includes specific resources and links to Yelp, TripAdvisor, Google Maps, and official websites
- Organized by day with detailed descriptions and helpful resource links

### 🎒 Smart Packing List Generator
- Personalized packing recommendations based on climate, trip duration, and activities
- Smart categorization of items (Essentials, Clothing, Toiletries, Electronics, etc.)
- Climate-aware suggestions for weather-appropriate gear

### 💰 Budget Calculator
- Automatic budget breakdown by category (Accommodation, Food, Transportation, Activities, etc.)
- Daily budget tracking
- Currency-aware calculations
- Per-person cost estimation for group trips

### ✨ Beautiful, Intuitive UI
- Smooth animations and interactive elements
- Responsive design works on mobile and desktop
- Sparkle effects and decorative patterns for a delightful experience
- Clean, modern interface with thoughtful typography

## Technology Stack

- **Frontend**: Next.js 15+ with React
- **Styling**: Tailwind CSS with custom design tokens
- **AI**: Groq LLM for fast, accurate travel planning
- **Fonts**: Inter (body text) and Quicksand (headings) for optimal readability
- **UI Components**: shadcn/ui components

## Getting Started

### Prerequisites
- Node.js 18+ 
- Groq API key

### Installation

1. Clone this repository or download the code
2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Add your `GROQ_API_KEY` to the environment variables in your Vercel project or `.env.local` file

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## How to Use

1. **Fill in Your Travel Details**:
   - Enter your destination
   - Specify your travel dates and number of travelers
   - Choose your travel style and interests
   - Set your budget range

2. **Generate Your Travel Plan**:
   - Click the "Generate Travel Plan" button
   - Wait for the AI to create personalized recommendations

3. **View Your Results**:
   - **Itinerary Tab**: See day-by-day activities with helpful resource links
   - **Packing List Tab**: Get a customized list of items to bring
   - **Budget Tab**: Review estimated costs and per-person breakdown

4. **Explore Resources**:
   - Click on resource links to read reviews, check hours, get directions, or make reservations
   - Links include Yelp for restaurants, TripAdvisor for attractions, and Google Maps for navigation

## Features Highlighted

### Resource Integration
Each activity in your itinerary includes direct links to:
- 🍴 **Yelp**: Restaurant reviews and ratings
- ⭐ **TripAdvisor**: Attraction information and traveler reviews
- 🗺️ **Google Maps**: Directions and location details
- 🌐 **Official Websites**: Ticket prices and operating hours

### Smart Recommendations
The AI considers:
- Climate and weather patterns
- Local culture and cuisine
- Popular attractions and hidden gems
- Budget constraints
- Trip duration and pacing

### Personalization
Get recommendations tailored to your:
- Travel style (adventurous, relaxing, cultural, etc.)
- Interests (food, nature, history, shopping, etc.)
- Group composition (solo, couple, family, friends)
- Physical abilities

## Tips for Best Results

- Be specific about your interests for more tailored recommendations
- Mention any dietary restrictions or accessibility needs
- Set a realistic budget to get accurate activity suggestions
- Specify the number of travelers for accurate per-person costs
- Consider seasonal information when planning

## Troubleshooting

**"Failed to generate travel plan"**
- Check that your Groq API key is correctly configured
- Ensure your internet connection is stable
- Try again with fewer travelers or a longer trip duration

**Resources not loading**
- Check your internet connection
- Some resources may vary by destination availability
- Links are generated based on AI recommendations

## Support

For issues or questions:
1. Check the Help button in the app for common questions
2. Review the settings to ensure your inputs are correct
3. Try generating a new plan with different parameters

## License

This project is open source and available under the MIT License.

---

**Made with ✈️ by travel enthusiasts, powered by Groq AI**
