<img src="https://user-images.githubusercontent.com/95444611/150992241-e17c333b-45a4-4314-8429-219356c8dd43.gif" width="100%"/>
const gradientBadge = require('gradient-badge');
exports.endpoint = function (req, resp) {
    resp.setHeader('Content-Type', 'image/svg+xml');
    resp.end(gradientBadge({
        subject: 'name',
        status: 'Amelie',
        gradient: ['b57acd', '11cbfa']
    }));
}
<!---
Loraria/Loraria is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
