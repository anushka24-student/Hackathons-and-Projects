# Design Philosophy

PranSetu is designed as a practical emergency healthcare platform that prioritizes core functionality over feature complexity. Features are designed to be rolled out in phases to ensure feasibility and reliability. The platform focuses on essential healthcare access needs in tier 2 and tier 3 cities across India, emphasizing simplicity, reliability, and immediate utility.

# Target User Demographics

## Primary Users
- **Patients & Families**: Ages 18-65, basic smartphone literacy, primarily Hindi/regional language speakers
- **Hospital Staff**: Nurses, administrators, doctors in government and private hospitals
- **Emergency Responders**: 108 ambulance operators, local health workers

## Geographic Focus
- **Tier 2 Cities**: Populations 50,000-1,00,000 (Aligarh, Bareilly, Jhansi, etc.)
- **Tier 3 Cities**: Populations 20,000-50,000 (District headquarters, tehsil towns)
- **Rural Areas**: Villages with PHCs and CHCs within 50km radius

# User Experience Design

## 1. Mobile-First Approach
### Screen Size Optimization
- **Primary Target**: 5-6 inch screens (720p-1080p resolution)
- **Secondary Support**: 4-5 inch screens (480p-720p resolution)
- **Touch Targets**: Minimum 48dp for easy finger navigation
- **Font Sizes**: Large, readable text (16sp minimum for body text)
### Interface Principles
- **One-Hand Operation**: Critical functions accessible with thumb
- **Visual Hierarchy**: Clear contrast, bold colors for emergency functions
- **Minimal Cognitive Load**: Maximum 3 taps to reach any core function
- **Offline-First**: Core features work without internet

## 2. Language & Localization
### Multi-Language Support
- **Primary Languages**: Hindi, English
- **Regional Languages**:
  - North: Punjabi, Haryanvi, Rajasthani
  - Central: Bhojpuri, Awadhi, Bundeli 
  - East: Bengali, Odia 
  - West: Gujarati, Marathi 
  - South: Tamil, Telugu, Kannada, Malayalam
### Cultural Considerations
- **Family-Centric Design**: Multiple emergency contacts, family member access 
- **Respect for Elders**: Large fonts, voice guidance for senior citizens 
- **Gender Sensitivity**: Female-only hospital options, women's health categories 
- **Religious Considerations**: Hospital filters for dietary restrictions, prayer times1. Accessibility Features1. For Low Digital Literacy1; Voice Navigation; Visual Icons; Tutorial Mode; Simplified Flow.2. For Physical Limitations2; High Contrast Mode; Large Text Mode; Voice Input; Haptic Feedback.
 
## Technical Architecture 
### 1. Progressive Web App (PWA) Design 
#### Why PWA for Indian Market 
 - No App Store Dependency : Direct installation via browser 
 - Smaller Download Size :2–5MB vs50–100MB native apps 
 - Automatic Updates :No manual update process 
 - Cross Platform :Works on Android,iOS,and KaiOS 
#### Offline Capabilities 
 - Service Worker :Cache critical hospital data and maps 
 - Local Storage :Store user preferences and emergency contacts 
 - Background Sync :Queue emergency calls when network returns 
 - Offline Maps :Pre-cached maps for50km radius1. Network Optimization1; Low Bandwidth Support;1; Data Compression;1; Lazy Loading;1; CDN Strategy.1; Connection Resilience.1; Retry Logic;1; Fallback Options;1; Network Detection;1; Caching Strategy.2. Backend Architecture2; Microservices Design. Database Strategy.