# LogisticsTrackingSystem

A Java-based system for tracking logistics, shipments, and parcels. 

## Overview
This system simulates the operations of a logistics tracking system, allowing users to track shipments as they move through different hubs, record scan events, manage delivery attempts, and handle proof of deliveries.

## Core Components
- **Customer**: Represents a customer utilizing the logistics services.
- **Parcel & Shipment**: Represents the items being shipped and the overall shipment details.
- **Hub**: Represents different nodes or hubs in the logistics network.
- **ScanEvent**: Tracks scanning events as a shipment moves through various checkpoints.
- **DeliveryAttempt & ProofOfDelivery**: Manages delivery attempts and successful delivery confirmations.
- **LogisticsTrackingSystem**: The main system coordinating the tracking operations.

## Running the Application
Ensure you have the Java Runtime Environment (JRE) installed to execute the compiled `.class` files.
```bash
java LogisticsTrackingSystem
```