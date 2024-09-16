# BC.Game Affiliate Program

Special conditions for you to customize referral program!

## Basic Advertisement HTML

Here's the basic HTML code to display an advertisement for BC.Game:

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BC.Game Advertisement</title>
<style>
body,html{margin:0;padding:0;height:100%;display:flex;justify-content:center;align-items:center}
.ad-image{max-width:100%;height:auto}
</style>
</head>
<body>
<a href="https://bc.game/i-2d63htoal-n/" target="_blank">
<img src="https://github.com/likhown/affiliate/blob/main/bc.game/5BTC_970x90_text_onebg.gif?raw=true" alt="BC.Game 5 BTC Bonus" class="ad-image">
</a>
</body>
</html>
```

## Ad Formats and CSS Customization

You can customize the ad display using CSS. Here are some examples:

### 1. Adjusting Ad Size

To display the ad in different formats, you can modify the `.ad-image` class:

```css
/* For a 300x250 banner */
.ad-image {
    width: 300px;
    height: 250px;
    object-fit: cover;
}

/* For a 728x90 leaderboard */
.ad-image {
    width: 728px;
    height: 90px;
    object-fit: cover;
}
```

### 2. Reducing Corner Radius

To reduce the corner radius of the image:

```css
.ad-image {
    border-radius: 5px; /* Adjust this value as needed */
}
```

### 3. Adding a Border

To add a border around the ad:

```css
.ad-image {
    border: 2px solid #000000;
}
```

## How to Apply Custom CSS

To apply custom CSS to the raw HTML:

1. Add your custom styles within the existing `<style>` tag in the HTML.
2. Or, create a separate CSS file and link it in the HTML head:

```html
<head>
    <!-- ... other head content ... -->
    <link rel="stylesheet" href="your-custom-styles.css">
</head>
```

## Example with Custom Styles

Here's an example incorporating some of these customizations:

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BC.Game Advertisement</title>
<style>
body,html{margin:0;padding:0;height:100%;display:flex;justify-content:center;align-items:center}
.ad-image{
    max-width:100%;
    height:auto;
    border-radius:5px;
    border:2px solid #000000;
}
/* Responsive design for different ad sizes */
@media (max-width: 300px) {
    .ad-image { width: 300px; height: 250px; object-fit: cover; }
}
@media (min-width: 301px) and (max-width: 728px) {
    .ad-image { width: 728px; height: 90px; object-fit: cover; }
}
</style>
</head>
<body>
<a href="https://bc.game/i-2d63htoal-n/" target="_blank">
<img src="https://github.com/likhown/affiliate/blob/main/bc.game/5BTC_970x90_text_onebg.gif?raw=true" alt="BC.Game 5 BTC Bonus" class="ad-image">
</a>
</body>
</html>
```

## Affiliate Details

- Affiliate Link: `https://bc.game/i-2d63htoal-n/`
- Bonus Offer: 25% bonus
- Expiration Date: 2024-08-30

Remember to update the affiliate link and bonus details as needed.

## Resources

- [BC.Game Affiliate Program](https://bc.game/affiliate) (replace with actual link if different)
- [Affiliate FAQ](https://bc.game/help/faq) (replace with actual link if different)

For any questions or support, please contact the BC.Game affiliate team.
