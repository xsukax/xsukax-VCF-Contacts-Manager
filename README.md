# 📱 xsukax VCF Contacts Manager

A powerful, modern web-based contact management application that allows you to import, edit, and export VCF (vCard) contact files directly in your browser. No server required, no data uploaded to the cloud - everything happens locally on your device.


## 🌟 Features

### 📂 File Management
- **Import VCF Files**: Support for standard vCard format (v3.0)
- **Export Modified Contacts**: Download your edited contacts as a new VCF file
- **Cross-Platform Compatible**: Works with contacts from iPhone, Android, Outlook, Gmail, and more
- **No Upload Required**: All processing happens locally in your browser

### 👤 Contact Management
- **View All Details**: Comprehensive display of contact information in organized cards
- **Inline Editing**: Edit contacts directly with intuitive form fields
- **Add New Contacts**: Create contacts from scratch with all standard fields
- **Smart Delete**: Safe deletion with custom confirmation modal (no popup blockers!)
- **Real-time Updates**: See changes immediately as you edit

### 🎯 Supported Contact Fields
- **Names**: Full name, given name, family name, middle name, prefix, suffix
- **Organization**: Company name and job title
- **Communication**: Multiple phone numbers and email addresses with type labels
- **Location**: Full address support (street, city, state, zip, country)
- **Additional**: Website URLs, notes, and birthday information
- **Type Support**: Different types for phones (CELL, WORK, HOME) and emails

### 🎨 Modern User Interface
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Beautiful Gradients**: Modern CSS with smooth animations and hover effects
- **Intuitive Navigation**: Easy-to-use interface with clear visual feedback
- **Status Messages**: Real-time feedback for all operations
- **Card-Based Layout**: Clean, organized display of contact information

## 🚀 Quick Start

### Option 1: Direct Download
1. Download the HTML file from this repository
2. Open it in any modern web browser
3. Click "Choose VCF File" to import your contacts
4. Start managing your contacts immediately!

### Option 2: Clone Repository
```bash
git clone https://github.com/xsukax/xsukax-VCF-Contacts-Manager.git
cd xsukax-VCF-Contacts-Manager
# Open xsukax-VCF-Contacts-Manager.html in your browser
```

## 💻 How to Use

### Importing Contacts
1. Click the **"📂 Choose VCF File"** button
2. Select your `.vcf` contact file from your device
3. All contacts will be automatically parsed and displayed

### Editing Contacts
1. Click the **"✏️ Edit"** button on any contact card
2. Modify any field directly in the form
3. Click **"✓ Save"** to confirm changes or **"✕ Cancel"** to discard

### Adding New Contacts
1. Click **"➕ Add Contact"** in the top controls
2. A new contact form will appear at the top of the list
3. Fill in the contact details and save

### Deleting Contacts
1. Click the **"🗑️ Delete"** button on any contact
2. Confirm deletion in the modal dialog
3. Contact is permanently removed from the list

### Exporting Contacts
1. Click **"💾 Save VCF"** to download your modified contacts
2. The file will be saved as `contacts.vcf` to your downloads folder
3. Import this file into any contacts application

## 🛠️ Technical Details

### Built With
- **Pure HTML5**: No frameworks or dependencies
- **Modern CSS3**: Flexbox, Grid, Gradients, Animations
- **Vanilla JavaScript**: ES6+ features for optimal performance
- **File API**: Browser-native file reading capabilities

### Browser Compatibility
- ✅ Chrome 60+ (Recommended)
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Security & Privacy
- 🔒 **100% Client-Side**: No data is sent to any server
- 🔒 **No Tracking**: No analytics or external scripts
- 🔒 **Local Processing**: All file parsing happens in your browser
- 🔒 **No Storage**: Files are not saved in browser storage

## 📋 VCF Format Support

The application supports the following vCard 3.0 properties:
- `FN` - Formatted Name
- `N` - Structured Name (Family, Given, Middle, Prefix, Suffix)
- `ORG` - Organization
- `TITLE` - Job Title
- `TEL` - Telephone Numbers (with TYPE parameters)
- `EMAIL` - Email Addresses (with TYPE parameters)
- `ADR` - Addresses (with TYPE parameters)
- `URL` - Website URLs
- `NOTE` - Notes
- `BDAY` - Birthday

## 🎯 Use Cases

### Personal Use
- Backup and edit your phone contacts
- Clean up duplicate or incomplete contact information
- Merge contacts from multiple devices
- Organize contact data before switching phones

### Business Use
- Manage company contact directories
- Import/export contacts between different business applications
- Clean up CRM data exports
- Prepare contact lists for marketing campaigns

### Development Use
- Test contact import/export functionality in applications
- Generate sample contact data for testing
- Convert between different contact formats
- Validate VCF file structures

## 🔧 Advanced Features

### Custom Modal System
- Bypasses popup blockers with custom CSS modals
- Smooth animations and professional styling
- Keyboard navigation support (Escape to cancel)
- Click-outside-to-close functionality

### Smart Contact Parsing
- Handles malformed VCF files gracefully
- Supports multiple phone numbers and emails per contact
- Preserves TYPE parameters for proper categorization
- Maintains data integrity during edit operations

### Responsive Design
- Mobile-first approach with touch-friendly interfaces
- Adaptive layouts for all screen sizes
- Optimized typography and spacing
- High contrast ratios for accessibility

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

### Bug Reports
- Open an issue with detailed description
- Include browser version and operating system
- Provide sample VCF files that cause issues (if applicable)

### Feature Requests
- Suggest new contact fields or formats
- Request UI/UX improvements
- Propose performance optimizations

### Code Contributions
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

### Common Issues
- **File not loading**: Ensure the file has a `.vcf` extension and contains valid vCard data
- **Missing contacts**: Check if the VCF file uses a supported vCard version (3.0 recommended)
- **Export issues**: Make sure your browser allows file downloads

### Getting Help
- 📧 Open an issue on GitHub
- 💬 Check existing issues for solutions
- 📖 Review the code comments for technical details

## 🔄 Changelog

### v1.0.0 (Latest)
- ✨ Initial release
- 📱 Full VCF import/export support
- ✏️ Inline contact editing
- 🗑️ Custom delete confirmation modal
- 📱 Responsive design
- 🎨 Modern UI with animations

## 🎯 Roadmap

### Upcoming Features
- 🔍 Search and filter contacts
- 📊 Bulk operations (delete multiple, import multiple files)
- 🏷️ Contact tagging and categorization
- 📤 Export to different formats (CSV, JSON)
- 🌙 Dark mode support
- ♿ Enhanced accessibility features

## ⭐ Star History

If you find this project useful, please consider giving it a star! It helps others discover the project and motivates continued development.

---

**Made with ❤️ for the open source community**

*xsukax VCF Contacts Manager - Making contact management simple, secure, and accessible to everyone.*
