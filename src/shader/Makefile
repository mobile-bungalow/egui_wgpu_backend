TARGETS = frag.spv vert.spv

all: $(TARGETS)

$(TARGETS):
	glslangValidator -V egui.frag
	glslangValidator -V egui.vert

clean:
	rm $(TARGETS)
