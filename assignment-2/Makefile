VEGA_RENDER = npx -p vega -p vega-lite -p canvas vl2png
SPECS = a2_earnest.json a2_deceptive.json
PNGS = $(SPECS:.json=.png)

.PHONY: all clean

all: $(PNGS)

a2_earnest.png: a2_earnest.json
	$(VEGA_RENDER) $< $@

a2_deceptive.png: a2_deceptive.json
	$(VEGA_RENDER) $< $@

clean:
	rm -f $(PNGS)
