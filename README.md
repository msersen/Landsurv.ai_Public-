# LandSurv.ai

**An AI Companion for Your Surveying Workflow**

LandSurv.ai is a free, browser-based platform that leverages artificial intelligence to enhance land surveying and civil engineering workflows. Built on open-source technology and designed with privacy in mind, it helps professionals accelerate their work while maintaining full control over their data.

🌐 **Live Application**: [land-surv-ai-874194952635.us-central1.run.app](https://land-surv-ai-874194952635.us-central1.run.app)

---

## 🎯 Core Philosophy

**No Accounts. No Downloads. No Barriers.**

LandSurv.ai runs entirely in your browser—no software installation, no account creation, and no login required. Your data stays on your device, and you maintain complete control over your privacy.

---

## ✨ Key Features

### 🤖 Specialized AI Agents

LandSurv.ai provides dedicated AI agents for different surveying tasks:

- **Raw Data Agent** - Process field measurements and raw survey data
- **Deed Agent** - Analyze legal descriptions and property deeds  
- **Civil Plan Expert** - Interpret multi-page civil engineering plans
- **DXF Agent** - Query and visualize CAD files
- **Centerline & Stationing Agent** - Horizontal alignment calculations
- **Point Editor** - Manage and organize survey point files
- **Image Analyzer** - AI-powered analysis of site photos
- **GIS Agent** - Work with GeoJSON and geographic data
- **Contouring Agent** - Generate topographic contours from elevation data
- **Profile & Cross Section Agent** - Create elevation profiles along alignments
- **GPS Stakeout** - Real-time field stakeout using device GPS
- **Fieldbook** - Digital field notes and calculations
- **LSVZ Meta-Agent** - High-level AI that reasons about entire projects

### 🎨 Powerful Tools

- **Interactive Drawing Canvas** - Visual plotting, annotation, and measurement tools
- **PDF Viewer with OCR** - Extract data from scanned plans with AI-powered uncertainty highlighting
- **COGO Calculations** - Coordinate geometry and bearing/distance computations
- **WMS Integration** - Connect to Web Map Services for background imagery
- **Layer Management** - Organize points, lines, and map overlays
- **Symbol Library** - Custom surveying symbols with AI generation
- **DXF Export** - Export project data to AutoCAD format
- **State Plane Support** - Multi-zone coordinate projection system
- **Closure Reports** - Automatic traverse closure analysis

---

## 📦 The .lsvz File Format

The **LandSurv.ai Zipped (.lsvz)** file is an open, AI-native container for land surveying projects. It's designed to break down data silos by encapsulating your entire workflow into a single, portable archive.

### Why .lsvz?

- ✅ **Complete Project Archive** - All source files, AI analysis, and generated data in one auditable package
- ✅ **AI-Ready** - Structured manifest enables advanced AI insights and automation
- ✅ **Open Standard** - Non-proprietary format prevents vendor lock-in
- ✅ **Interoperable** - Seamless data transfer between software and field equipment

### Technical Structure

The .lsvz file is a standard ZIP archive containing:
- `manifest.json` - Complete session state with settings, chat histories, and data
- Original source files (raw, PDF, DXF, images, etc.)

### License

The .lsvz format specification is published under **Creative Commons Attribution 4.0 International (CC BY 4.0)** to encourage widespread adoption. Use it freely, even commercially—just give credit to LandSurv.ai.

📖 [View Full Format Documentation](https://land-surv-ai-874194952635.us-central1.run.app)

---

## 🚀 Getting Started

### Option 1: Use the Live Application (Recommended)

1. Visit [land-surv-ai-874194952635.us-central1.run.app](https://land-surv-ai-874194952635.us-central1.run.app)
2. Get a free Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey)
3. Enter your API key in Settings
4. Start analyzing your survey data!

### Option 2: Self-Host

**Prerequisites**: Node.js v18+

```bash
# Clone the repository
git clone https://github.com/msersen/LandSurv.ai-Refactored.git
cd LandSurv.ai-Refactored

# Install dependencies
npm install

# Set your Gemini API key
echo "GEMINI_API_KEY=your_key_here" > .env.local

# Run locally
npm run dev
```

Open http://localhost:3000 in your browser.

---

## 💡 How It Works

### Accelerate Your Drafting Process

Provide a raw data file or deed, and LandSurv.ai generates an initial draft of survey-accurate features or legal descriptions—significantly reducing manual transcription time while you focus on professional review.

### Enhance Your Document Review

The AI serves as a second set of eyes, analyzing scanned deeds, plans, and photos to identify potential issues: faint lines, conflicting callouts, or smudges that could represent critical monuments. You make the final, informed decision.

### Portable Intelligence

All project data and AI analysis is captured in the .lsvz file—a "mission package" that enables autonomous systems, drones, or robots to operate with greater intelligence in the field.

---

## 🛠️ Technology Stack

Built on powerful open-source technologies:

- **React 19** - Modern UI framework
- **Vite** - Fast build tool
- **Google Gemini API** - Advanced AI capabilities
- **PDF.js** - PDF rendering and processing
- **Tesseract.js** - Optical character recognition
- **Proj4.js** - Coordinate projection transformations
- **Google Maps API** - Interactive mapping
- **JSZip** - File compression for .lsvz format
- **DXF-Writer** - CAD file export

View complete technology attributions in the app's Technologies page.

---

## 📊 Latest Updates (v1.24.0 - Current Beta)

- ✨ **New**: Layer Manager panel for centralized visibility control
- ✨ **New**: Profile & Cross Section Agent with visual chart display
- ✨ **New**: Polyline drawing tool with breakline support
- 🎨 **Enhanced**: Symbol Manager with AI-powered symbol generation
- 🔧 **Fixed**: Contouring artifacts near breaklines
- 📱 **Improved**: Responsive layout for mobile devices

See [Release Log](https://land-surv-ai-874194952635.us-central1.run.app) for full version history.

---

## 💰 Pricing & Support

### Free to Use

The core platform is completely free. Connect your own Gemini API key (free from Google) and access full functionality at no cost.

### Support Development

If you find value in LandSurv.ai, you can support continued innovation:

- 💵 **PayPal Donations** - Direct support via PayPal
- 🪙 **LSVC Token** - Future-forward model using the LandSurv Credit (LSVC) ERC-20 token for premium features

---

## 🤝 Contributing

We believe in building upon the collective work of the community. The .lsvz format is open-source and we welcome:

- Format specification improvements
- Integration with other surveying software
- Tool development using .lsvz files
- Community feedback and feature requests

---

## 📝 License

- **Application**: Copyright © 2025 LandSurv.ai - All Rights Reserved
- **.lsvz Format**: Creative Commons Attribution 4.0 International (CC BY 4.0)

---

## 🔗 Links

- 🌐 **Live App**: [land-surv-ai-874194952635.us-central1.run.app](https://land-surv-ai-874194952635.us-central1.run.app)
- 📖 **Documentation**: Available within the application
- 🔧 **API Key**: [Get Free Gemini API Key](https://aistudio.google.com/app/apikey)
- ⚖️ **Format License**: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---

## 🎯 Mission Statement

LandSurv.ai is more than a product—it's a new layer in the digital toolkit for surveyors and civil engineers. We're building open standards, enhancing existing data formats, and creating a future where technology and professional expertise work hand-in-hand.

**Democratizing Access. Empowering Professionals. Building the Future.**

---

*Built with ❤️ for the surveying and civil engineering community*
