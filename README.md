# p5.js Web App Converter

Convert any p5.js editor sketch into a fullscreen progressive web app for iOS and Android. Perfect for creating interactive demos and exhibits.

## Usage

1. Open the converter in your web browser
2. Paste any p5.js editor URL (e.g., `https://editor.p5js.org/username/sketches/sketchid`)
3. Choose your options:
   - **Make the p5 navbar invisible**: Hides the p5.js editor navigation bar
   - **Disable Touch Inputs**: Prevents touch interactions (useful for kiosk mode)
4. Optionally enter a custom title for your web app
5. Click "Convert to Web App"
6. Once the sketch loads, tap the share button in Safari (iOS) or Chrome (Android)
7. Select "Add to Home Screen"
8. Your sketch will now run as a fullscreen web app!

## Supported URL Formats

- `https://editor.p5js.org/username/sketches/sketchid`
- `https://preview.p5js.org/username/present/sketchid`
- `https://preview.p5js.org/username/full/sketchid`


## Technical Details

- Adds [Progressive Web App features](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps) to the sketch
- Uses iframe sandboxing for security
- Supports device sensors and permissions (camera, microphone, geolocation, etc.)
- Prevents default browser behaviors when touch inputs are disabled
- Dynamically updates meta tags based on the loaded sketch

## Disclaimer & Terms of Use

This tool is provided for educational and creative purposes only without any warranties or guarantees. By using this converter, you agree to:

1. **Security Notice**: This tool loads external content from p5.js editor. Users are responsible for verifying the safety and legitimacy of the content they load. Only use URLs from trusted sources.

2. **Liability**: The creator(s) of this converter are not responsible for any damages, losses, or consequences that may result from using this tool or any converted web apps. Users assume all risks associated with running external code.

3. **Usage Rights**: This tool is for personal and educational use only. Users are responsible for complying with all applicable laws and p5.js terms of service when using converted sketches.

4. **Content Responsibility**: Users are solely responsible for any content they load through this converter. The creator(s) do not endorse or take responsibility for any third-party content.

5. **Permissions**: Users must ensure they have necessary rights and permissions for any content they convert and distribute using this tool.

## License

See [LICENSE](LICENSE) file for details.
