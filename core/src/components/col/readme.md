# ion-col

Columns are cellular components of the [grid](../Grid) system and go inside of a [row](../Row).
They will expand to fill their row. All content within a grid should go inside of a column.

See [Grid Layout](/docs/layout/grid) for more information.


## Column attributes

By default, columns will stretch to fill the entire height of the row.
There are several attributes that can be added to a column to customize this behavior.

| Property              | Description                                                                                                 |
|-----------------------|-------------------------------------------------------------------------------------------------------------|
| align-self-start      | Adds `align-self: flex-start`. The column will be vertically aligned at the top.                            |
| align-self-center     | Adds `align-self: center`. The column will be vertically aligned in the center.                             |
| align-self-end        | Adds `align-self: flex-end`. The column will be vertically aligned at the bottom.                           |
| align-self-stretch    | Adds `align-self: stretch`. The column will be stretched to take up the entire height of the row.           |
| align-self-baseline   | Adds `align-self: baseline`. The column will be vertically aligned at its baseline.                         |



<!-- Auto Generated Below -->


## Properties

| Property   | Attribute   | Description                                                                                                                                                                          | Type                  |
| ---------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------- |
| `offsetLg` | `offset-lg` | The amount to offset the column for lg screens, in terms of how many columns it should shift to the right of the total available.                                                    | `string \| undefined` |
| `offsetMd` | `offset-md` | The amount to offset the column for md screens, in terms of how many columns it should shift to the right of the total available.                                                    | `string \| undefined` |
| `offsetSm` | `offset-sm` | The amount to offset the column for sm screens, in terms of how many columns it should shift to the right of the total available.                                                    | `string \| undefined` |
| `offsetXl` | `offset-xl` | The amount to offset the column for xl screens, in terms of how many columns it should shift to the right of the total available.                                                    | `string \| undefined` |
| `offsetXs` | `offset-xs` | The amount to offset the column for xs screens, in terms of how many columns it should shift to the right of the total available.                                                    | `string \| undefined` |
| `offset`   | `offset`    | The amount to offset the column, in terms of how many columns it should shift to the right of the total available.                                                                   | `string \| undefined` |
| `pullLg`   | `pull-lg`   | The amount to pull the column for lg screens, in terms of how many columns it should shift to the left of the total available.                                                       | `string \| undefined` |
| `pullMd`   | `pull-md`   | The amount to pull the column for md screens, in terms of how many columns it should shift to the left of the total available.                                                       | `string \| undefined` |
| `pullSm`   | `pull-sm`   | The amount to pull the column for sm screens, in terms of how many columns it should shift to the left of the total available.                                                       | `string \| undefined` |
| `pullXl`   | `pull-xl`   | The amount to pull the column for xl screens, in terms of how many columns it should shift to the left of the total available.                                                       | `string \| undefined` |
| `pullXs`   | `pull-xs`   | The amount to pull the column for xs screens, in terms of how many columns it should shift to the left of the total available.                                                       | `string \| undefined` |
| `pull`     | `pull`      | The amount to pull the column, in terms of how many columns it should shift to the left of the total available.                                                                      | `string \| undefined` |
| `pushLg`   | `push-lg`   | The amount to push the column for lg screens, in terms of how many columns it should shift to the right of the total available.                                                      | `string \| undefined` |
| `pushMd`   | `push-md`   | The amount to push the column for md screens, in terms of how many columns it should shift to the right of the total available.                                                      | `string \| undefined` |
| `pushSm`   | `push-sm`   | The amount to push the column for sm screens, in terms of how many columns it should shift to the right of the total available.                                                      | `string \| undefined` |
| `pushXl`   | `push-xl`   | The amount to push the column for xl screens, in terms of how many columns it should shift to the right of the total available.                                                      | `string \| undefined` |
| `pushXs`   | `push-xs`   | The amount to push the column for xs screens, in terms of how many columns it should shift to the right of the total available.                                                      | `string \| undefined` |
| `push`     | `push`      | The amount to push the column, in terms of how many columns it should shift to the right of the total available.                                                                     | `string \| undefined` |
| `sizeLg`   | `size-lg`   | The size of the column for lg screens, in terms of how many columns it should take up out of the total available. If `"auto"` is passed, the column will be the size of its content. | `string \| undefined` |
| `sizeMd`   | `size-md`   | The size of the column for md screens, in terms of how many columns it should take up out of the total available. If `"auto"` is passed, the column will be the size of its content. | `string \| undefined` |
| `sizeSm`   | `size-sm`   | The size of the column for sm screens, in terms of how many columns it should take up out of the total available. If `"auto"` is passed, the column will be the size of its content. | `string \| undefined` |
| `sizeXl`   | `size-xl`   | The size of the column for xl screens, in terms of how many columns it should take up out of the total available. If `"auto"` is passed, the column will be the size of its content. | `string \| undefined` |
| `sizeXs`   | `size-xs`   | The size of the column for xs screens, in terms of how many columns it should take up out of the total available. If `"auto"` is passed, the column will be the size of its content. | `string \| undefined` |
| `size`     | `size`      | The size of the column, in terms of how many columns it should take up out of the total available. If `"auto"` is passed, the column will be the size of its content.                | `string \| undefined` |


## CSS Custom Properties

| Name                           | Description                                 |
| ------------------------------ | ------------------------------------------- |
| `--ion-grid-column-padding`    | Padding for the Column                      |
| `--ion-grid-column-padding-lg` | Padding for the Column on lg screens and up |
| `--ion-grid-column-padding-md` | Padding for the Column on md screens and up |
| `--ion-grid-column-padding-sm` | Padding for the Column on sm screens and up |
| `--ion-grid-column-padding-xl` | Padding for the Column on xl screens and up |
| `--ion-grid-column-padding-xs` | Padding for the Column on xs screens and up |
| `--ion-grid-columns`           | The number of total Columns in the Grid     |


----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
