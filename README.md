# Project SMS


A single combined CRUD application that merges Inventory, Crafting, Objectives, Food Spoilage, and Map Discovery would function as a Survival Management System.

Combined CRUD Application: Survival Management System
1. Inventory & Resources

Create items (tools, materials, food)

Read current inventory and quantities

Update item amounts, condition, or location

Delete used, dropped, or destroyed items

2. Crafting System

Create crafting recipes

Read recipe requirements and outputs

Update ingredients or results

Delete obsolete recipes

Crafting pulls directly from inventory data and updates it after crafting.

3. Objectives / Quest Log

Create survival objectives (build shelter, find food)

Read active and completed objectives

Update progress or completion status

Delete finished or failed objectives

Objectives can depend on crafted items or discovered locations.

4. Food Spoilage Tracking

Create food items with freshness values

Read spoilage status

Update decay over time

Delete spoiled food

Food exists as inventory items but includes time-based data.

5. Map & Location Discovery

Create discovered locations

Read location details and notes

Update exploration status or resources found

Delete abandoned or irrelevant locations

Locations can unlock objectives or crafting materials.

Data Relationships

Inventory items are used by crafting recipes

Crafted items update inventory

Objectives reference items, food, or locations

Food items decay over time inside inventory

Locations unlock new objectives or resources

Summary

This combined CRUD application models the core survival loop:
explore → collect → craft → survive → progress
All systems are data-driven and interact through shared records while remaining purely CRUD-based.
