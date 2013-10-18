Example
=======

var container = new Pimple();

container.set("user", container.share(function(c) {
    return new User();
}));

http://github.com/mikegerwitz/easejs.git
