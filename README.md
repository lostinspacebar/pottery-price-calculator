# Garnet Pricing Model

A practical pricing guide for Garnet's functional pottery. Use the model as a starting point, then compare the result with similar work and the venue where the piece will be sold.

## Price the piece

Start with an adjustable base price (Garnet's usual range is **$20–$25**), then add or subtract for the piece's qualities:

- **Base:** Set the starting price to suit the piece. Use less only for something especially small, simple, and easy to glaze; account for more expensive materials when relevant.
- **Details:** add about $5 for each detail, such as a handle, foot, basic carving or design, or a glaze treatment beyond a basic dip glaze.
- **Size:** add about $5 for each size step above small; larger pieces may warrant more.
- **Personal value:** add $0–$20 if you particularly love the piece and would be happy to keep it if it does not sell.
- **Uniqueness:** add $0–$20 for a unique piece.
- **Popular design:** add $0–$10 for a popular style, such as a travel mug or boob mug.
- **Motivation to sell:** subtract $0–$10 if you especially want the piece to sell.

These are judgment-based adjustments, not mandatory fees. Avoid double-counting the same quality under multiple adjustments.

## Gallery listing price

The calculator treats the **25% gallery commission**, **8.9% sales tax**, and **10% studio fee** as shares of the listed price. The sales tax is included in the gallery price rather than added on top. Under this assumption, the maker's share is 56.1% of the listed price:

```text
maker share = 1 − 0.25 − 0.089 − 0.10 = 0.561

piece price = base + (details × $5) + (size steps × $5)
              + personal value + uniqueness + popular design
              − quick-sale discount

gallery listing price = piece price ÷ 0.561
```

For example, a $22.50 base price with no adjustments results in a suggested gallery listing price of about **$40.11**. The gallery commission is about $10.03, sales tax about $3.57, and studio fee about $4.01, leaving $22.50. Confirm the gallery's accounting method and tax rules; use its actual method if it differs from this assumption.

## Check the price before deciding

1. **Research comparable work:** What are similar items selling for? Consider whether the artist is well known and whether the comparison is a gallery or Etsy price.
2. **Consider the market:** Local markets differ; for example, San Francisco prices may be higher than Denver prices.
3. **Consider the occasion and venue:** Gallery prices are usually higher than small-market prices, and holiday pieces may sell for more.
4. **Account for your work and costs:** Include time, materials, glazes, firing, and studio access. Decide what you need to recover before settling on the piece price.
5. **Set three reference prices:** Record your minimum acceptable price, your stretch price, and the price that would make you happiest. For gallery sales, enter the amount you want to retain as the piece price and use the calculator to convert it to a gallery listing price.

The final price should make sense for the piece, its costs, the market, and what you are willing to accept. The model is a guide, not a substitute for checking comparable sales or the gallery's exact terms.

## Use the calculator

Open [`index.html`](index.html) in a browser. Adjust the base price and piece adjustments; the suggested gallery listing price and fee breakdown update automatically. No installation or build step is required.
