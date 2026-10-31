Edits are proposed as drafts and become part of your project only when you choose Apply. This gives you an explicit chance to check exact values and totals.

## Choose an operation

| Operation | Purpose |
| --- | --- |
| Exact demographic tuple | Change one population group's size |
| Scale population total | Change a location's total while distributing its population |
| Add population group | Add a group using known type, culture and religion identifiers |
| Remove population group | Remove the selected group |
| Rebalance proportions | Redistribute a demographic axis while preserving the total |

A demographic tuple identifies a population group by type, culture and religion. Additional source fields are handled conservatively; invalid or ambiguous data is reported.

## Calculations

| Calculation | Example input | Effect |
| --- | --- | --- |
| Set exact value / target | `120` | Set the selected size or total to 120 source units |
| Add / subtract absolute value | `-5` | Subtract 5 source units |
| Increase / decrease percent | `10` | Increase by 10 percent |
| Multiply by factor | `1.25` | Multiply by 1.25 |

Use a decimal point for numeric values. Negative changes must not result in invalid negative population sizes. The editor validates the proposal before it can be applied.

## Review, Apply and Discard

**Review draft** calculates a proposal. Compare the Original, Working and Draft totals and the change from Working. **Apply** confirms the current reviewed proposal. **Discard** removes the pending form and proposal.

If you edit an input after reviewing, the proposal is no longer current. Review again before applying. Save and export continue to use only Working values, even while a draft is visible.

## Add or remove groups

For an added group, choose identifiers from the definitions loaded with the selected game installation. Arbitrary new cultures, religions or population types cannot be created here. Specify a valid size and review the result.

Removing a group can change the location total. If your intention is to redistribute its share while preserving the total, use [Rebalance proportions](ratios.html) instead.

## Undo and redo

Undo and redo operate on confirmed actions. Resolve pending drafts first by applying or discarding them. A game-data migration establishes a new source boundary and clears the previous undo history. Save a separate project copy before undertaking a major migration.
