all: part1 part2

part1: prepare
	python3 part1.py input.txt

part1_simple: prepare
	python3 part1.py -d simple.txt

part2: prepare
	python3 part2.py input.txt

part2_simple: prepare
	python3 part2.py -d simple.txt

.PHONY: prepare
prepare:
	[ -f "simple.txt" ] || touch simple.txt
	[ -f "input.txt" ] || touch input.txt
	[ -f "part1.py" ] || (cp template.py part1.py && pip install -r requirements.txt)
	[ -f "part2.py" ] || cp template.py part2.py

clean:
	rm part1.py part2.py simple.txt input.txt