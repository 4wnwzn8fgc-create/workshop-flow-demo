# Workshop Flow – Interactive Concept Demo

A browser-based concept demonstration of digital shelf-location tracking for an aircraft engine and component repair workshop.

## Live demo
Once GitHub Pages is enabled: https://4wnwzn8fgc-create.github.io/workshop-flow-demo/

## How to enable GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Set **Branch: main**, folder **/(root)**, then click **Save**.
4. Open the link above once GitHub confirms deployment.

## Demonstration features
- Simulate scanning the receiving department and work order/asset identification.
- Validate whether preceding work stages are complete.
- Assign the next free shelf location or reject an invalid transfer.
- View simulated work orders, storage locations, work in progress and deviations.
- Reset sample data using the **Reset demo** button.

This is **fictional demonstration data only**. It does not use real company information, connect to a production management system, authenticate users, or persist records to a server.

## Future implementation
A production application would be deployed to the company's own network, use a database to manage inventory locations and movements, and access the existing production-management system through a restricted read-only integration.
