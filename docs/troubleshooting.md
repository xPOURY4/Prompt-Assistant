# 🆘 Troubleshooting Guide - Prompt Assistant

Solve common issues and get the most out of Prompt Assistant, available on the [Chrome Web Store](https://chromewebstore.google.com/detail/prompt-assistant-ai-promp/khjjnklmccfmbidflahakjameliioidm).

## 🔧 Installation Issues

### Extension Won't Install
**Symptoms**: Error message during installation or extension not appearing in toolbar

**Solutions**:
1. **Check Chrome version**: Ensure Chrome 88+ is installed
2. **Clear browser cache**: Go to Settings → Privacy → Clear browsing data
3. **Disable conflicting extensions**: Temporarily disable other extensions
4. **Try incognito mode**: Install in a private browsing session
5. **Restart browser**: Close and reopen Chrome completely

### Extension Icon Missing
**Symptoms**: Successfully installed but icon not visible in toolbar

**Solutions**:
1. **Check extension status**: Go to `chrome://extensions/` and ensure it's enabled
2. **Pin to toolbar**: Click the puzzle piece icon and pin Prompt Assistant
3. **Reset toolbar**: Right-click toolbar → Reset to default
4. **Check display mode**: Ensure you're not in fullscreen mode

## 🔑 API Key Problems

### Invalid API Key Error
**Error**: "API key not valid" or "Authentication failed"

**Solutions**:
1. **Verify key format**: Must start with "AIza..." and be 39 characters long
2. **Check Google Cloud Console**:
   - Go to [Google Cloud Console](https://console.cloud.google.com/)
   - Enable Gemini API for your project
   - Verify billing is set up
3. **Copy key carefully**: Ensure no extra spaces or characters
4. **Try generating new key**: Create a fresh API key if current one fails

### API Key Keeps Disappearing
**Symptoms**: Need to re-enter API key frequently

**Solutions**:
1. **Check browser settings**: Ensure cookies and local storage are enabled
2. **Disable private browsing**: Use normal browsing mode for persistent storage
3. **Browser permissions**: Grant storage permissions to the extension
4. **Update browser**: Use latest Chrome version for better compatibility

### Rate Limit Exceeded
**Error**: "Quota exceeded" or "Too many requests"

**Solutions**:
1. **Wait for reset**: Rate limits reset every minute
2. **Monitor usage**: Check your Google Cloud Console for API usage
3. **Upgrade plan**: Consider paid tier for higher limits
4. **Use cached features**: Rely on local analysis when possible

## 🌐 Language and Display Issues

### Wrong Language Interface
**Symptoms**: UI showing in unexpected language

**Solutions**:
1. **Manual language switch**: Click language toggle in header
2. **Clear browser cache**: Reset language preferences
3. **Check Chrome settings**: Ensure preferred language is set correctly
4. **Restart extension**: Disable and re-enable in `chrome://extensions/`

### RTL/LTR Text Direction Problems
**Symptoms**: Text flowing in wrong direction, especially for Persian content

**Solutions**:
1. **Auto-detection settings**: Enable automatic text direction detection
2. **Manual override**: Use direction controls in settings
3. **Mixed content**: Check individual text blocks for proper direction
4. **Font rendering**: Ensure Persian fonts are loading correctly

### Missing Characters or Fonts
**Symptoms**: Boxes, question marks, or missing letters in Persian text

**Solutions**:
1. **Install fonts**: Ensure Vazirmatn font is loaded
2. **Check font fallbacks**: Enable font substitution in browser settings
3. **Clear font cache**: Restart browser to reload fonts
4. **Update graphics drivers**: Ensure proper text rendering support

## ⚡ Performance Issues

### Slow Loading Times
**Symptoms**: Extension takes long time to open or respond

**Solutions**:
1. **Clear extension data**: Go to settings → Reset data
2. **Reduce cache size**: Lower cache limits in advanced settings
3. **Close other tabs**: Free up browser memory
4. **Update Chrome**: Use latest browser version
5. **Check system resources**: Ensure adequate RAM and CPU

### Frequent Crashes or Freezes
**Symptoms**: Extension becomes unresponsive or crashes browser

**Solutions**:
1. **Disable other extensions**: Check for conflicts
2. **Reduce memory usage**: Lower cache and history limits
3. **Safe mode**: Run Chrome with minimal extensions
4. **Hardware acceleration**: Disable in Chrome settings if causing issues
5. **Reinstall extension**: Remove and reinstall from Chrome Web Store

### API Requests Timing Out
**Symptoms**: "Request timed out" errors during analysis or optimization

**Solutions**:
1. **Check internet connection**: Ensure stable, fast connection
2. **Increase timeout**: Extend timeout duration in settings
3. **Retry mechanism**: Enable automatic retries for failed requests
4. **Simplify prompts**: Break complex requests into smaller parts
5. **Server status**: Check Google Cloud status page for outages

## 📊 Feature-Specific Issues

### Smart Questions Not Generating
**Symptoms**: No questions appear after entering initial request

**Solutions**:
1. **Check API key**: Ensure valid Google Gemini API key is configured
2. **Request detail**: Provide more detailed initial descriptions
3. **Category selection**: Choose appropriate category before proceeding
4. **Language settings**: Verify output language preferences
5. **Try different wording**: Rephrase your initial request

### Prompt Analysis Not Working
**Symptoms**: No analysis scores or feedback appearing

**Solutions**:
1. **Enable real-time analysis**: Check settings for analysis preferences
2. **Minimum length**: Ensure prompt meets minimum character requirements
3. **Clear language**: Use clear, unambiguous language in prompts
4. **API availability**: Verify API quota hasn't been exceeded
5. **Browser compatibility**: Update to supported browser version

### Export Functions Failing
**Symptoms**: Cannot save or export prompts to files

**Solutions**:
1. **Browser permissions**: Allow downloads and file access
2. **Pop-up blockers**: Disable for the extension
3. **Download folder**: Ensure download directory is accessible
4. **File format**: Try different export formats (TXT, JSON, CSV)
5. **Storage space**: Check available disk space

### History Not Saving
**Symptoms**: Prompts not appearing in history or favorites

**Solutions**:
1. **Storage permissions**: Grant local storage access
2. **Private browsing**: Use normal mode for data persistence
3. **Storage limits**: Check if storage quota is full
4. **Manual save**: Use explicit save buttons when available
5. **Data corruption**: Reset and reimport if necessary

## 🔒 Security and Privacy Concerns

### Data Safety Verification
**Concerns**: Questions about data collection and storage

**Verification Steps**:
1. **Review privacy policy**: Check extension's data handling practices
2. **Local storage only**: Verify data stays in browser
3. **Network monitoring**: Use developer tools to check what's transmitted
4. **Source code**: Review open-source components if available
5. **Permissions audit**: Check extension permissions in Chrome

### Suspicious Behavior
**Symptoms**: Unexpected network requests or data access

**Immediate Actions**:
1. **Disable extension**: Turn off immediately
2. **Review permissions**: Check what access was granted
3. **Contact support**: Report suspicious activity
4. **Browser security scan**: Run antivirus on browser
5. **Consider removal**: Uninstall if concerns persist

## 🛠️ Advanced Troubleshooting

### Developer Console Debugging
For technical users experiencing persistent issues:

1. **Open developer tools**: Press F12 in Chrome
2. **Console tab**: Look for error messages
3. **Network tab**: Monitor API requests and responses
4. **Application tab**: Check local storage and settings
5. **Extensions tab**: Verify extension status and permissions

### Reset to Factory Settings
When all else fails:

1. **Export important data**: Save prompts and templates
2. **Clear all data**: Go to settings → Advanced → Reset all
3. **Reinstall extension**: Remove and reinstall from Chrome Web Store
4. **Reconfigure**: Set up API key and preferences again
5. **Import data**: Restore saved prompts and templates

### Contact Support
If issues persist after trying these solutions:

**Email**: hexquant@gmail.com
**Include**:
- Chrome version
- Extension version
- Operating system
- Detailed error description
- Steps to reproduce
- Console error messages (if any)

**Telegram**: [@HexQuantHub](https://t.me/HexQuantHub)
**Website**: [hexquant.xyz](https://hexquant.xyz)

## 📋 Prevention Tips

### Best Practices for Stability
1. **Regular updates**: Keep Chrome and extension updated
2. **Clean installation**: Avoid modifying extension files
3. **Resource management**: Don't overload browser with too many tabs
4. **Backup data**: Export important prompts regularly
5. **Monitor usage**: Keep track of API quota consumption

### Performance Optimization
1. **Cache management**: Clear cache periodically
2. **History limits**: Set reasonable history retention periods
3. **API efficiency**: Use local features when possible
4. **Network stability**: Ensure reliable internet connection
5. **System maintenance**: Keep computer optimized and updated

---

**Still experiencing issues?** Contact our support team at hexquant@gmail.com or visit [x(twitter)](https://x.com/TheTealPourya) for personalized help. 
