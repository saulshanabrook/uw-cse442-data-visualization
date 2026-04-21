VEGA_RENDER = npx -p vega -p vega-lite -p canvas vl2png
SPECS = hours-per-month.json conception-vs-sunshine.json
PNGS = $(SPECS:.json=.png)

.PHONY: all clean

all: $(PNGS)

hours-per-month.png: hours-per-month.json
	$(VEGA_RENDER) $< $@

conception-vs-sunshine.png: conception-vs-sunshine.json
	$(VEGA_RENDER) $< $@

clean:
	rm -f $(PNGS)
