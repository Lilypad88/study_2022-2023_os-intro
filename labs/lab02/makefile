.PHONY: all clean

all: report.pdf report.docx

report.pdf: report.md
	pandoc report.md -o report.pdf  # <- Здесь должна быть табуляция!

report.docx: report.md
	pandoc report.md -o report.docx  # <- И здесь тоже!

clean:
	rm -f report.pdf report.docx  # <- И здесь!
