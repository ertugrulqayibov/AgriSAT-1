# AgriSat - Kənd Təsərrüfatı Sİ Sistemi

**Agricultural AI Assistant for Karabagh Region**

## Overview

AgriSat is an AI-powered agricultural assistant system designed for the Karabagh region, utilizing satellite data analysis and Natural Language Processing technology to provide intelligent farming recommendations.

### Key Features

- **Satellite Monitoring**: Real-time monitoring of agricultural areas using Sentinel-2 satellite data
- **Vegetation Indices Analysis**: Analysis of NDVI, NDWI, NPCRI, NDRE, NDPI, NDKI and other vegetation indices
- **Precision Agriculture**: Optimal crop planning based on satellite data analysis
- **Natural Language Interface**: AI assistant in Azerbaijani language for agricultural queries
- **Interactive Mapping**: Visual analysis of crop areas and vegetation indices

## System Description

**Title**: AgriSat - Kənd Təsərrüfatı Sİ Sistemi  
**Description**: Qarabağ əkinçilik məlumat bazası və Təbii Dil Emalı texnologiyası ilə dəstəklənən kənd təsərrüfatı AI köməkçisi

## Sample Questions

### General Agricultural Queries
- Ağdamda hansı məhsullar əkilə bilər? *(What crops can be grown in Agdam?)*
- Qarabağda ən çox hansı məhsullar əkilir? *(What crops are most commonly grown in Karabagh?)*
- 2024-cü ildə Ağdamda hansı məhsullar əkilib? *(What crops were grown in Agdam in 2024?)*

### Vegetation Index Queries
- Şuşada NDVI və NDWI göstəriciləri ən yüksək olan ərazilər hansılardır? *(Which areas in Shusha have the highest NDVI and NDWI indicators?)*
- NDRE və NPCRI göstəriciləri üzrə ən əlverişli əkin sahələri haradadır? *(Where are the most favorable crop areas based on NDRE and NPCRI indicators?)*
- Hansı bölgədə NDPI ən yüksəkdir və orada nə əkə bilərik? *(Which region has the highest NDPI and what can we grow there?)*
- NDVI və NDRE göstəriciləri ən yüksək olan ərazilərdə nə əkə bilərik? *(What can we grow in areas with the highest NDVI and NDRE indicators?)*

### Irrigation and Water Management
- Qarabağda hansı əkin sahələri daha çox suvarma tələb edir? *(Which crop areas in Karabagh require more irrigation?)*

### Land Suitability Assessment
- Əkin üçün uyğun olan (NDVI yuxarı) ərazilər hansılardır? *(Which areas are suitable for crops (high NDVI)?)*

### Database Information
- Baza strukturu və mövcud sahələr haqqında məlumat ver. *(Provide information about database structure and available fields.)*

## Technical Specifications

### Monitoring Capabilities
- **Accuracy**: 10-meter spatial analysis precision
- **Update Frequency**: Data refreshed every 5 days
- **Analysis**: 6+ vegetation indices analysis
- **Coverage**: Complete Karabagh region agricultural areas

### Vegetation Indices Supported
- **NDVI** (Normalized Difference Vegetation Index)
- **NDWI** (Normalized Difference Water Index)
- **NPCRI** (Normalized Pigment Chlorophyll Ratio Index)
- **NDRE** (Normalized Difference Red Edge)
- **NDPI** (Normalized Difference Phenology Index)
- **NDKI** (Normalized Difference Kernel Index)

## System Architecture

### Frontend Features
- Responsive web interface
- Real-time chat functionality
- Interactive example prompts
- Navigation between main chat and monitoring views
- Virtual scrolling for performance optimization
- Local storage for chat history and preferences
- Rate limiting and input validation

### Backend Integration (In Development)
- Database connectivity for crop records
- Satellite data processing
- AI model integration for crop recommendations
- Server-side operations for:
  - Displaying all crop records
  - Adding new crop records
  - Updating crop records
  - Showing crop status

## Development Status

### Completed (September 2025)
- ✅ Analysis and Planning
- ✅ Frontend interface design
- ✅ Basic chat functionality

### In Progress (October 2025)
- 🔄 Backend Integration
- 🔄 Satellite data processing system

### Next Phase (November 2025)
- ⚪ Interactive mapping and visualization
- ⚪ Complete monitoring system

### Planned Launch Date
**December 2025** - Full system operational launch

## Usage Guidelines

### Best Practices
- Ask specific questions with vegetation index references for optimal results
- Use precise location names when querying about specific areas
- Include relevant agricultural terms for better AI understanding

### Demo Mode Notice
Currently operating in demo mode with limited functionality. Backend integration required for full operational capability.

### Rate Limiting
- Maximum 5 messages per 10-second window
- Message length limited to 500 characters
- Input validation and sanitization implemented

## Server Actions (Future Implementation)
- Display all crop records
- Add new crop record
- Update crop record
- Show crop status

## Technical Implementation Details

### Performance Optimizations
- Virtual scrolling for chat messages
- Debounced scroll handling
- Response caching (24-hour expiry)
- Local storage management with size limits

### Security Features
- Input validation and sanitization
- XSS prevention
- Rate limiting
- Error handling and timeout management

### Accessibility
- ARIA labels for navigation
- Keyboard navigation support
- Responsive design for mobile devices
- High contrast color scheme

## Contact and Support

For technical support or feature requests, please refer to the system documentation or contact the development team.

---

*AgriSat - Empowering precision agriculture in Karabagh through satellite technology and artificial intelligence.*
