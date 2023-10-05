# Hello-World
package.json
{
  "name": "project",
  "version": "1.0.0",
  "dependencies": {
    "left-pad": "1.0.0",
    "c": "file:../c-1",
    "d2": "file:../d2-1"
  },
  "resolutions": {
    "d2/left-pad": "1.1.1",
    "c/**/left-pad": "^1.1.2"
  }
}

  "name": "my-awesome-package"
}

yarn add [name]
node_modules/[name]
https://registry.npmjs.org/[name]/-/[name]-[version].tgz
{
  "version": "1.0.0"
}
{
  "description": "My short description of my awesome package"
}
{
  "keywords": ["short", "relevant", "keywords", "for", "searching"]
}
{
  "license": "MIT",
  "license": "(MIT or GPL-3.0)",
  "license": "SEE LICENSE IN LICENSE_FILENAME.txt",
  "license": "UNLICENSED"
}

{
  "homepage": "https://your-package.org"
}
{
  "bugs": "https://github.com/user/repo/issues"
}
{
  "repository": { "type": "git", "url": "https://github.com/user/repo.git" },
  "repository": "github:user/repo",
  "repository": "gitlab:user/repo",
  "repository": "bitbucket:user/repo",
  "repository": "gist:a1b2c3d4e5f"
}
{
  "author": {
    "name": "Your Name",
    "email": "you@example.com",
    "url": "http://your-website.com"
  },
  "author": "Your Name <you@example.com> (http://your-website.com)"
}
{
  "contributors": [
    { "name": "Your Friend", "email": "friend@example.com", "url": "http://friends-website.com" }
    { "name": "Other Friend", "email": "other@example.com", "url": "http://other-website.com" }
  ],
  "contributors": [
    "Your Friend <friend@example.com> (http://friends-website.com)",
    "Other Friend <other@example.com> (http://other-website.com)"
  ]
}

{
  "files": ["filename.js", "directory/", "glob/*.{js,json}"]
}
{
  "main": "filename.js"
}

{
  "bin": "bin.js",
  "bin": {
    "command-name": "bin/command-name.js",
    "other-command": "bin/other-command"
  }
}

{
  "man": "./man/doc.1",
  "man": ["./man/doc.1", "./man/doc.2"]
}


{
  "directories": {
    "lib": "path/to/lib/",
    "bin": "path/to/bin/",
    "man": "path/to/man/",
    "doc": "path/to/doc/",
    "example": "path/to/example/"
  }
}

{
  "scripts": {
    "build-project": "node build-project.js"
  }
}

{
  "config": {
    "port": "8080"
  }
}
{
  "dependencies": {
    "package-1": "^3.1.4"
  }
}

{
  "devDependencies": {
    "package-2": "^0.4.2"
  }
}

{
  "peerDependencies": {
    "package-3": "^2.7.18"
  }
}

{
  "peerDependenciesMeta": {
    "package-3": {
      "optional": true
    }
  }
}

{
  "optionalDependencies": {
    "package-5": "^1.6.1"
  }
}
{
  "bundledDependencies": ["package-4"]
}

