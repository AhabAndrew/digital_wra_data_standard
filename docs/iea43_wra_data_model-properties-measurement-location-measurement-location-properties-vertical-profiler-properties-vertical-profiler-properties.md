## items Type

`object` ([Vertical Profiler Properties](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-vertical-profiler-properties-vertical-profiler-properties.md))

# items Properties

| Property                                                    | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| :---------------------------------------------------------- | :------------ | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [device_datum_plane_height_m](#device_datum_plane_height_m) | `number`      | Optional | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-properties-measurement-location-measurement-location-properties-vertical-profiler-properties-vertical-profiler-properties-properties-device-datum-plane-height-m.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/device_datum_plane_height_m") |
| [height_reference_id](#height_reference_id)                 | Not specified | Optional | cannot be null | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-definitions-height-reference.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/height_reference_id")                                                                                                                                             |
| [device_orientation_deg](#device_orientation_deg)           | `number`      | Optional | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-properties-measurement-location-measurement-location-properties-vertical-profiler-properties-vertical-profiler-properties-properties-device-orientation-deg.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/device_orientation_deg")           |
| [orientation_reference_id](#orientation_reference_id)       | `string`      | Optional | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-definitions-orientation-reference.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/orientation_reference_id")                                                                                                                                   |
| [date_from](#date_from)                                     | `string`      | Optional | cannot be null | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-definitions-date-from.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/date_from")                                                                                                                                                              |
| [date_to](#date_to)                                         | `string`      | Optional | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-definitions-date-to.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/date_to")                                                                                                                                                                  |
| [notes](#notes)                                             | `string`      | Optional | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-definitions-notes.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/notes")                                                                                                                                                                      |
| [update_at](#update_at)                                     | `string`      | Optional | can be null    | [IEA Wind Resource Assessment - Data Model](iea43_wra_data_model-definitions-date-of-update.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/update_at")                                                                                                                                                         |

## device_datum_plane_height_m

The datum plane height of the remote sensing device where the datum feature is defined here: <http://data.windenergy.dtu.dk/ontologies/view/ontolidar/en/page/DatumFeature> . For lidars the datum feature is usually the window and for sodars it is usually the base of the device. These datum plane heights are also usually referred to as above ground level however it may be above sea level or above a platform level.

`device_datum_plane_height_m`

*   is optional

*   Type: `number` ([Device Datum Plane Height \[m\]](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-vertical-profiler-properties-vertical-profiler-properties-properties-device-datum-plane-height-m.md))

*   can be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-vertical-profiler-properties-vertical-profiler-properties-properties-device-datum-plane-height-m.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/device_datum_plane_height_m")

### device_datum_plane_height_m Type

`number` ([Device Datum Plane Height \[m\]](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-vertical-profiler-properties-vertical-profiler-properties-properties-device-datum-plane-height-m.md))

### device_datum_plane_height_m Examples

```json
0.5
```

```json
1
```

## height_reference_id

The height reference frame that is used to measure the item height. E.g. onshore this is ground level i.e. the item is 0.5 m above ground level. Offshore is a bit different as it can be 20 m above mean sea level or 20 m above lowest astronomical tide.

`height_reference_id`

*   is optional

*   Type: unknown ([Height Reference](iea43\_wra_data_model-definitions-height-reference.md))

*   cannot be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-definitions-height-reference.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/height_reference_id")

### height_reference_id Type

unknown ([Height Reference](iea43\_wra_data_model-definitions-height-reference.md))

### height_reference_id Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                        | Explanation |
| :--------------------------- | :---------- |
| `"ground_level"`             |             |
| `"mean_sea_level"`           |             |
| `"lowest_astronomical_tide"` |             |
| `"other"`                    |             |

### height_reference_id Default Value

The default value is:

```json
"ground_level"
```

## device_orientation_deg

The orientation that the remote sensing device is installed relative to north.

`device_orientation_deg`

*   is optional

*   Type: `number` ([Device Orientation \[deg\]](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-vertical-profiler-properties-vertical-profiler-properties-properties-device-orientation-deg.md))

*   can be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-vertical-profiler-properties-vertical-profiler-properties-properties-device-orientation-deg.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/device_orientation_deg")

### device_orientation_deg Type

`number` ([Device Orientation \[deg\]](iea43\_wra_data_model-properties-measurement-location-measurement-location-properties-vertical-profiler-properties-vertical-profiler-properties-properties-device-orientation-deg.md))

### device_orientation_deg Constraints

**maximum**: the value of this number must smaller than or equal to: `360`

**minimum**: the value of this number must greater than or equal to: `0`

## orientation_reference_id

The orientation reference the item is measured against. E.g. magnetic north.

`orientation_reference_id`

*   is optional

*   Type: `string` ([Orientation Reference](iea43\_wra_data_model-definitions-orientation-reference.md))

*   can be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-definitions-orientation-reference.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/orientation_reference_id")

### orientation_reference_id Type

`string` ([Orientation Reference](iea43\_wra_data_model-definitions-orientation-reference.md))

### orientation_reference_id Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value              | Explanation |
| :----------------- | :---------- |
| `"magnetic_north"` |             |
| `"true_north"`     |             |
| `"grid_north"`     |             |

## date_from

The date from when these properties are active. If these properties follow a change, then this Date From should equal the previous Date To. The format of this date should follow ISO 8601 with the 'T' required. If a timezone is used, it is essential that this timezone is the same as the logger timezone.

`date_from`

*   is optional

*   Type: `string` ([Date From](iea43\_wra_data_model-definitions-date-from.md))

*   cannot be null

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-definitions-date-from.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/date_from")

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

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-definitions-date-to.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/date_to")

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

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-definitions-notes.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/notes")

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

*   defined in: [IEA Wind Resource Assessment - Data Model](iea43\_wra_data_model-definitions-date-of-update.md "https://raw.githubusercontent.com/IEA-Task-43/digital_wra_data_standard/master/schema/iea43\_wra_data_model.schema.json#/properties/measurement_location/items/properties/vertical_profiler_properties/items/properties/update_at")

### update_at Type

`string` ([Date of Update](iea43\_wra_data_model-definitions-date-of-update.md))

### update_at Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

### update_at Examples

```json
"2020-07-28T20:49:13"
```
