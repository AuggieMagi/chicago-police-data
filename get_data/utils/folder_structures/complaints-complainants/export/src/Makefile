# -*- coding: utf-8 -*-

# Authors:	Roman Rivera (Invisible Institute)
# individual/complaints-complainants_2000-2018_2018-07_18-060-294/export/src/Makefile

.PHONY: all clean
# Additional files created: export.log, export.yaml,
# complaints-complainants_2000-2018_2018-07_profiles.csv.gz

all: \
		output/complaints-complainants_2000-2018_2018-07.csv.gz

output/complaints-complainants_2000-2018_2018-07.csv.gz: \
		src/export.py \
		input/complaints-complainants_2000-2018_2018-07.csv.gz
	python3 $<


clean:
	rm output/*


# done
