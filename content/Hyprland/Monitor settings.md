 
```
monitor= DP-2, 2560x1440@240, 0x0, 1.00, bitdepth, 10, cm, srgb, sdrbrightness, 1.7

monitorv2 {
		output = DP-2
		mode = 2560x1440@240
		position = 0x0
		scale = 1
		bitdepth = 10
		supports_hdr = 1
		sdr_min_luminance = 0.005
		sdr_max_luminance = 400
#	}


monitor= DP-3, 2560x1440@170, 2560x0, 1.00, bitdepth, 10, cm, srgb, sdrbrightness, 1
```


[^1]: monitorv2 didnt work, replace srgb with hdr incase
