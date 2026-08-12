# TC-INV-001 – Verify Item Equip and Unequip

> Portfolio test case for demonstrating inventory functional coverage.

## Module
Inventory / Equipment

## Type
Functional

## Priority
High

## Objective
Verify that an eligible item can be equipped, reflected in the character state, and removed from the equipment slot.

## Preconditions
- Player owns an eligible equipment item.
- Inventory is accessible.
- Equipment slot is available.

## Test Steps
1. Open the inventory.
2. Navigate to the appropriate equipment category.
3. Select an eligible item.
4. Equip the item.
5. Observe the equipment slot and character statistics.
6. Unequip the item.

## Expected Result
The item is equipped in the correct slot, relevant statistics update as designed, and the item can be unequipped without loss or duplication.

## Pass Criteria
Inventory state, equipment slot, item ownership, and displayed statistics remain consistent throughout the operation.