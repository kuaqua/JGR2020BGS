1) seasonal water temperature and DIC for Figure 3

1-1) filename, "water_depth_water_temperature_season.txt"
matrix data, 1618 x 3
season, water depth (unit: m), water temperature (unit: Celcius degree)

1-2) filename, "water_depth_DIC_season.txt"
matrix data, 736 x 3
season, water depth (unit: m), DIC (unit: mg/L)



2) seasonal average of water temperature and DIC for Figure 4

2-1) filename, "water_temperature_season.txt"
matrix data, 7 x 4
season, water temperature for water surface (unit: Celcius degree), water temperature for bottom (unit: Celcius degree), water temperature for a river (unit: Celcius degree)

2-2) filename, "DIC_season.txt"
matrix data, 7 x 4
season, DIC for water surface (unit: mg/L), DIC for bottom (unit: mg/L), DIC for a river (unit: mg/L)



3) seasonal average of mixing depth, Brunt–Väisälä frequency, and intrusion depth for Figure 5

3-1) filename, "mixing_depth_season.txt"
matrix data, 7 x 2
season, mixing depth / water depth (unit: -)

3-2) filename, "BruntV_season.txt"
matrix data, 7 x 2
season, Brunt–Väisälä frequency (unit: 1/s)

3-3) filename, "intrusion_depth_season.txt"
matrix data, 7 x 2
season, intrusion depth / water depth (unit: -)



4) water surface temperature vs water surface DIC, water surface temperature vs hypolimnion DIC, river DIC vs hypolimnion DIC, Brunt–Väisälä frequency vs water surface DIC, Brunt–Väisälä frequency vs hypolimnion DIC, Brunt–Väisälä frequency vs river DIC, Brunt–Väisälä frequency vs water surface temperature, mixing depth vs water surface temperature, and Brunt–Väisälä frequency vs mixing depth for Figure 6

4-1) filename, "water_surface_temperature_water_surface_DIC.txt"
matrix data, 148 x 3
season, water surface temperature  (unit: Celcius degree), water surface DIC (unit: mg/L)

4-2) filename, "water_surface_temperature_hypolimnion_DIC.txt"
matrix data, 148 x 3
season, water surface temperature  (unit: Celcius degree), hypolimnion DIC (unit: mg/L)

4-3) filename, "river_DIC_hypolimnion_DIC.txt"
matrix data, 148 x 3
season, river DIC  (unit: mg/L), hypolimnion DIC (unit: mg/L)

4-4) filename, "Brunt–Väisälä_frequency_water_surface_DIC.txt"
matrix data, 148 x 3
season, Brunt–Väisälä frequency  (unit: 1/s), water surface DIC (unit: mg/L)

4-5) filename, "Brunt–Väisälä_frequency_hypolimnion_DIC.txt"
matrix data, 148 x 3
season, Brunt–Väisälä frequency  (unit: 1/s), hypolimnion DIC (unit: mg/L)

4-6) filename, "Brunt–Väisälä_frequency_river_DIC.txt"
matrix data, 148 x 3
season, Brunt–Väisälä frequency  (unit: 1/s), river DIC (unit: mg/L)

4-7) filename, "Brunt–Väisälä_frequency_water_surface_temperature.txt"
matrix data, 148 x 3
season, Brunt–Väisälä frequency  (unit: 1/s), water surface temperature  (unit: Celcius degree)

4-8) filename, "mixing_depth_water_surface_temperature.txt"
matrix data, 148 x 3
season, mixing depth  (unit: m), water surface temperature  (unit: Celcius degree)

4-9) filename, "Brunt–Väisälä_frequency_mixing_depth.txt"
matrix data, 148 x 3
season, Brunt–Väisälä frequency  (unit: 1/s), mixing depth  (unit: m)



5) seasonal average of delta DIC for Figure 7

5-1) filename, "water_depth_delta_DIC.txt"
matrix data, 31 x 3
season, water depth  (unit: m), delta DIC (unit: mg/L)



6) seasonal average of NEP for Figure 9

6-1) filename, "NEP_season.txt"
matrix data, 5 x 2
season, NEP (unit: mg  C/m^3/d)



7) Computational outputs from Fantom for Figure 8
Filenames:
YYL_2008summer-000000.dat
YYL_2008summer-014400.dat
YYL_2008summer-028800.dat

7-1) Format of computatinal outputs
Filenames, "YYL_2008summer-000000.dat", "YYL_2008summer-014400.dat" and "YYL_2008summer-028800.dat"
row 1: time	"computational time"
row 2: dz	"vertical mesh interval from the bottom to the top of computational domain"
row 3: limit_depth	0.05
row 4: items	number	k_offset	center_x	center_y	delta_x	delta_y	btm_k	sfc_k	btm_z	sfc_z	container_i	container_j	local_i	local_j	dry_wet
row 5 up to row 1560: column	"corresponding number to row 4"
row 1561 up to row 3116: "column number"	tracer2	"tracer at each vertical mesh"
row 3117 up to row 4672: "column number"	tracer0	"vertical velocity at each vertical mesh"
row 4673 up to row 6228: "column number"	salinity	"salinity at each vertical mesh"
row 6229 up to row 7784: "column number"	v	"v at each vertical mesh"
row 7785 up to row 9340: "column number"	tracer1	"tracer at each vertical mesh"
row 9341 up to row 10896: "column number"	psi	"dissipation at each vertical mesh"
row 10897 up to row 12452: "column number"	u	"u at each vertical mesh"
row 12453 up to row 14008: "column number"	dic	"dic at each vertical mesh"
row 14009 up to row 15564: "column number"	w	"w at each vertical mesh"
row 15565 up to row 17120: "column number"	tke	"turbulent kinetic energy at each vertical mesh"
row 17121 up to row 18676: "column number"	temperature	"water temperature at each vertical mesh"
We did not use "tracer2", "tracer0", "salinity" and "dic".

