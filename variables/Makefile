AUTHOR = "Codular"

build:
	@echo "Building my project for $(AUTHOR)!"
	@mkdir build
	@find . -type f | grep ".txt" | xargs -I{} bash -c "cat {} | sed 's/__AUTHOR__/$(AUTHOR)/g' > build/{}"

clean:
	@echo "Cleaning up the build folder"
	@rm -rf build
