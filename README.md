# 🍎 Swift iOS Boilerplate

A comprehensive, production-ready iOS boilerplate built with **SwiftUI** and modern iOS development practices. This template provides a solid foundation for building native iOS apps with integrated services, consistent design patterns, and enterprise-grade architecture.

## 🚀 What's Included

### **🏗️ Architecture**
- **SwiftUI** - Modern declarative UI framework
- **Flow-Based Organization** - Screens grouped by user journey
- **Theme System** - Consistent design with automatic dark mode support
- **Component Library** - Reusable UI components with comprehensive documentation

### **🛠️ Built-in Services**
- **API Service** - Secure HTTP client with async/await support
- **User Management** - Complete user state management with multiple storage backends
- **Push Notifications** - Automated user engagement campaigns
- **Superwall Integration** - Strategic paywall monetization system
- **Singleton Pattern** - Thread-safe service management

### **📁 Project Structure**
```
Views/              # Flow-based view organization
├── App/           # App-level views (splash, errors)
├── Onboarding/    # User onboarding flow
├── Main/          # Core app functionality
└── [CustomFlow]/  # Additional user flows

Components/        # Reusable UI components
├── Global/       # App-wide components
├── Shared/       # Cross-flow components
└── [FlowName]/   # Flow-specific components

Utils/            # Core services and utilities
Theme/            # Design system implementation
Assets.xcassets/  # Colors, images, data assets
```

## 🏃‍♂️ Quick Start

1. **Open in Xcode**
   ```bash
   open Swift-Boilerplate.xcodeproj
   ```

2. **Build and Run**
   - Select your target device/simulator
   - Press `⌘ + R` to build and run
   - Or click the Play button in Xcode

3. **Start Development**
   - All views are organized by user flow
   - Use the theme system for consistent styling
   - Follow the architectural patterns in existing code

## 🎨 Key Features

### **🎯 Design System**
- **Auto-Generated Colors** - Colors managed through `Assets.xcassets`
- **Comprehensive Typography** - 25+ font styles for every use case
- **Button Styles** - Consistent interactive elements with animations
- **Dark Mode Support** - Automatic switching with system preferences
- **Accessibility First** - Built-in support for all users

### **📱 Production Ready**
- **Flow-Based Navigation** - Organized by user journey
- **Error Handling** - Comprehensive error management
- **State Management** - Proper SwiftUI state patterns
- **Performance Optimized** - Memory management and optimization
- **Testing Support** - Unit and UI testing infrastructure

### **🔒 Enterprise Grade**
- **Secure Services** - HTTPS-only with proper authentication
- **Privacy Compliant** - GDPR/CCPA ready patterns
- **Scalable Architecture** - Designed for growing teams
- **Documentation Driven** - Extensive inline documentation

## 📖 Documentation

- **`component-rules.mdc`** - Component development guidelines
- **`view-rules.mdc`** - View architecture standards  
- **`util-rules.mdc`** - Service integration documentation
- **Theme System** - Complete design system documentation
- **Architecture Rules** - Comprehensive development guidelines

## 🎯 Perfect For

- **Native iOS Apps** - Full platform feature access
- **Enterprise Applications** - Scalable, maintainable architecture
- **Team Development** - Consistent patterns and conventions
- **MVP to Production** - Rapid development with production-ready code
- **Learning SwiftUI** - Modern iOS development best practices

## 🛠️ Requirements

- **Xcode 15.0+** - Latest development environment
- **iOS 17.0+** - Modern iOS features and APIs
- **Swift 5.9+** - Latest Swift language features
- **macOS 14.0+** - For development machine

## 🌟 Architecture Highlights

- **Theme-First Design** - All UI uses the centralized theme system
- **Component Reusability** - Smart extraction patterns for maintainable code
- **Service Integration** - Built-in utilities for common app needs
- **Flow Organization** - Logical grouping of related screens
- **Accessibility by Default** - Every component supports all users
- **Documentation Standards** - Self-documenting code patterns

---

**Build beautiful, accessible iOS apps with confidence!** 🚀 