## items Type

`object` ([Interference Structures](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures.md))

# items Properties

| Property                                                              | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| :-------------------------------------------------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [structure_type_id](#structure_type_id)                               | `string` | Required | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures-properties-structure-type.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/structure_type_id")                                  |
| [orientation_from_mast_centre_deg](#orientation_from_mast_centre_deg) | `number` | Optional | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures-properties-orientation-from-mast-centre-deg.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/orientation_from_mast_centre_deg") |
| [orientation_reference_id](#orientation_reference_id)                 | `string` | Optional | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-definitions-orientation-reference.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/orientation_reference_id")                                                                                                                                                                                  |
| [distance_from_mast_centre_mm](#distance_from_mast_centre_mm)         | `number` | Optional | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures-properties-distance-from-mast-centre-mm.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/distance_from_mast_centre_mm")         |
| [date_from](#date_from)                                               | `string` | Required | cannot be null | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-definitions-date-from.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/date_from")                                                                                                                                                                                                             |
| [date_to](#date_to)                                                   | `string` | Optional | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-definitions-date-to.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/date_to")                                                                                                                                                                                                                 |
| [notes](#notes)                                                       | `string` | Optional | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-definitions-notes.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/notes")                                                                                                                                                                                                                     |
| [update_at](#update_at)                                               | `string` | Optional | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-definitions-date-of-update.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/update_at")                                                                                                                                                                                                        |

## structure_type_id

The type of structure that is causing an interference in the sensor's measurements.

`structure_type_id`

*   is required

*   Type: `string` ([Structure Type](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures-properties-structure-type.md))

*   can be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures-properties-structure-type.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/structure_type_id")

### structure_type_id Type

`string` ([Structure Type](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures-properties-structure-type.md))

### structure_type_id Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                | Explanation |
| :------------------- | :---------- |
| `"lightning_finial"` |             |
| `"aviation_light"`   |             |
| `"guy_wires"`        |             |
| `"other"`            |             |

## orientation_from_mast_centre_deg

The orientation of the interference structure, relative to the centre of the mast, causing an impact on the sensor's measurements.

`orientation_from_mast_centre_deg`

*   is optional

*   Type: `number` ([Orientation from Mast Centre \[deg\]](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures-properties-orientation-from-mast-centre-deg.md))

*   can be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures-properties-orientation-from-mast-centre-deg.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/orientation_from_mast_centre_deg")

### orientation_from_mast_centre_deg Type

`number` ([Orientation from Mast Centre \[deg\]](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures-properties-orientation-from-mast-centre-deg.md))

### orientation_from_mast_centre_deg Constraints

**maximum**: the value of this number must smaller than or equal to: `360`

**minimum**: the value of this number must greater than or equal to: `0`

## orientation_reference_id

The orientation reference the item is measured against. E.g. magnetic north.

`orientation_reference_id`

*   is optional

*   Type: `string` ([Orientation Reference](iea43\_wra_data_model-definitions-orientation-reference.md))

*   can be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-definitions-orientation-reference.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/orientation_reference_id")

### orientation_reference_id Type

`string` ([Orientation Reference](iea43\_wra_data_model-definitions-orientation-reference.md))

### orientation_reference_id Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value              | Explanation |
| :----------------- | :---------- |
| `"magnetic_north"` |             |
| `"true_north"`     |             |
| `"grid_north"`     |             |

## distance_from_mast_centre_mm

The distance from the mast centre to the interference structure causing an impact on the sensor's measurements.

`distance_from_mast_centre_mm`

*   is optional

*   Type: `number` ([Distance from Mast Centre \[mm\]](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures-properties-distance-from-mast-centre-mm.md))

*   can be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures-properties-distance-from-mast-centre-mm.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/distance_from_mast_centre_mm")

### distance_from_mast_centre_mm Type

`number` ([Distance from Mast Centre \[mm\]](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-measurement-point-measurement-point-properties-interference-structures-interference-structures-properties-distance-from-mast-centre-mm.md))

### distance_from_mast_centre_mm Examples

```json
900
```

## date_from

The date from when these properties are active. If these properties follow a change, then this Date From should equal the previous Date To. The format of this date should follow ISO 8601 with the 'T' required. If a timezone is used, it is essential that this timezone is the same as the logger timezone.

`date_from`

*   is required

*   Type: `string` ([Date From](iea43\_wra_data_model-definitions-date-from.md))

*   cannot be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-definitions-date-from.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/date_from")

### date_from Type

`string` ([Date From](iea43\_wra_data_model-definitions-date-from.md))

### date_from Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

### date_from Examples

```json
"2020-07-28T20:00:00"
```

## date_to

The final end date for when these properties are active. If these properties are currently active please use null. If null is not allowed please use 2100-01-01T00:00:00. The format of this date should follow ISO 8601 with the 'T' required. If a timezone is used, it is essential that this timezone is the same as the logger timezone.

`date_to`

*   is optional

*   Type: `string` ([Date To](iea43\_wra_data_model-definitions-date-to.md))

*   can be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-definitions-date-to.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/date_to")

### date_to Type

`string` ([Date To](iea43\_wra_data_model-definitions-date-to.md))

### date_to Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

### date_to Examples

```json
"2020-07-28T20:00:00"
```

```json
"2100-01-01T00:00:00"
```

## notes

Notes relating to these properties.

`notes`

*   is optional

*   Type: `string` ([Notes](iea43\_wra_data_model-definitions-notes.md))

*   can be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-definitions-notes.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/notes")

### notes Type

`string` ([Notes](iea43\_wra_data_model-definitions-notes.md))

### notes Examples

```json
"I can write anything I want here."
```

## update_at

The date these properties were last updated.

`update_at`

*   is optional

*   Type: `string` ([Date of Update](iea43\_wra_data_model-definitions-date-of-update.md))

*   can be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-definitions-date-of-update.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/measurement_point/items/properties/interference_structures/items/properties/update_at")

### update_at Type

`string` ([Date of Update](iea43\_wra_data_model-definitions-date-of-update.md))

### update_at Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

### update_at Examples

```json
"2020-07-28T20:49:13"
```
