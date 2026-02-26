# PERMISSIONANALYZER-APPLICATION
Short Description

PermissionAnalyzer is an Android security application that analyzes installed apps and evaluates their permission risks using static analysis and rule-based classification.

Full Description (Recommended for README)

PermissionAnalyzer is an Android-based security analysis tool designed to help users understand the privacy risks associated with application permissions. The application scans installed apps on a device, extracts declared permissions using the Android PackageManager API, and classifies each application into Low, Medium, or High risk levels based on dangerous permission usage. 

The system performs fully offline static analysis, ensuring user privacy while providing transparent and interpretable security insights. 

Features

Scans installed Android applications

Extracts declared permissions automatically

Identifies dangerous permissions

Risk classification (Low / Medium / High)

User-friendly interface

Detailed permission view per application

Offline processing (no internet required)

Technologies Used

Kotlin

Android Studio

Android SDK

PackageManager API

RecyclerView

How It Works

The app scans installed applications.

Permissions are extracted using Android APIs.

Dangerous permissions are identified.

A rule-based algorithm calculates risk levels.

Results are displayed in a simple interface. 

Risk Classification Logic

High Risk: ≥ 5 dangerous permissions

Medium Risk: 2–4 dangerous permissions

Low Risk: ≤ 1 dangerous permission 

Purpose

This project was developed as part of a Mobile & Wireless Security course and demonstrates how static permission analysis can improve user awareness and mobile privacy.
