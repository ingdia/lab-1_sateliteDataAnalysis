#!/bin/bash
(head -n 1 ../raw_data/satelite_temperature_data.csv && sort -t, -k3,3nr ../raw_data/satelite_temperature_data.csv | head -n 10) > highest_temp.csv
(head -n 1 ../raw_data/satelite_temperature_data.csv && grep "Nigeria" ../raw_data/satelite_temperature_data.csv | sort -t, -k4,4nr) > humidity_data_Nigeria.csv
