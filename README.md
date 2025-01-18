# ff-5mp-profiles
Configuration &amp; Filament Profiles for the FlashForge 5M (Pro)

# Usage
The base path for user configuration files is 
```
%appdata%\Orca-Flashforge\user
```

## Process Files
Process files go here
```
%appdata%\Orca-Flashforge\user\process
```

## Filament Files
Filament files go here
```
%appdata%\Orca-Flashforge\user\process
```

### Additional Information
Orcaslicer/Orca-Flashforge has issues with profile 'Iiheritance' and import custom files

If you have issues importing any of these files, creating your own profiles in Orcaslier/Orca-Flashforge and then copying the options from the json file is the quickest alternative.

Example json
```
{
    "bridge_speed": "20",
    "brim_type": "auto_brim",
    "default_acceleration": "5000",
    "enable_arc_fitting": "0",
    "from": "User", - ignore
    "gap_infill_speed": "120",
    "inherits": "0.20mm Standard @Flashforge AD5M Pro 0.4 Nozzle", - ignore
    "initial_layer_infill_speed": "40",
    "initial_layer_speed": "30",
    "inner_wall_acceleration": "3000",
    "inner_wall_speed": "200",
    "internal_bridge_speed": "35",
    "internal_solid_infill_acceleration": "3500",
    "internal_solid_infill_speed": "190",
    "is_custom_defined": "0",
    "name": "0.20mm 0.4 Nozzle Cheap PLA",
    "outer_wall_acceleration": "2000",
    "outer_wall_speed": "150",
    "overhang_2_4_speed": "30",
    "overhang_3_4_speed": "15",
    "print_settings_id": "0.20mm 0.4 Nozzle Cheap PLA", - ignore
    "slow_down_layers": "2",
    "slowdown_for_curled_perimeters": "1",
    "sparse_infill_acceleration": "65%",
    "sparse_infill_speed": "200",
    "support_speed": "120",
    "top_surface_acceleration": "1000",
    "top_surface_speed": "150",
    "travel_acceleration": "5000",
    "version": "1.8.0.0", - ignore
    "wall_generator": "arachne"
}
```
