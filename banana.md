# Web App Code Maintenance
Every time something in a web application is changed or updated, all of the tasks in the simplified list should be completed for maitinence. This reflects standard industry workflow
- Update documentation
- Run unit component, functional, and integration tests to ensure all components work both alone and together.
- Run end-to-end tests simulating user interaction and ensure app behaves as expected
- Audit packages for outdated and vulnerable packages
- Run code formatter, linter, etc to check code quality
- Check accessibility and responsiveness.
- Transpile JavaScript with Babel or another tool for wider browser support
- Concatenate all JS files into a single file for faster loading
- Concatenate all CSS files into a single file for faster loading
- Minify and uglify all first and third party JavaScript and CSS files
- Move all production assets into a distribution directory to separate them from development files
- Deploy application into staging environment for final testing
