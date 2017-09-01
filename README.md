# TESTING
HOW TO USE GIT

### How to connect to your remote MongoDB server 
https://ianlondon.github.io/blog/mongodb-auth/

### Running Raw/Direct/Native MongoDB Queries Through Mongoose.js
note: lower mongoose version might not be compatable with higher node version, it will fail silently. 
http://www.bainweb.com/2015/06/running-rawdirectnative-mongodb-queries.html

### when terminal ask me again for ssh password after reboot my machine:
run `ssh-add -A` (https://superuser.com/questions/1127067/macos-keeps-asking-my-ssh-passphrase-since-i-updated-to-sierra)

### module.exports vs exports
Exports is just module.exports’s little helper. Your module returns module.exports to the caller ultimately, not exports. All exports does is collect properties and attach them to module.exports
If there’s something attached to module.exports already, everything on exports is ignored.good explanation:
https://medium.com/@geekguy/javascript-modues-exports-vs-exports-whats-the-difference-9a61cdb99386
