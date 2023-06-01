(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var k;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var ea=ca(this);function n(a,b){if(b)a:{var c=ea;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
n("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
n("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=ea[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return fa(aa(this))}})}return a});
function fa(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function ha(a){return a.raw=a}
function t(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];if(b)return b.call(a);if("number"==typeof a.length)return{next:aa(a)};throw Error(String(a)+" is not an iterable or ArrayLike");}
function ia(a){if(!(a instanceof Array)){a=t(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ka(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var la="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ka(d,e)&&(a[e]=d[e])}return a};
n("Object.assign",function(a){return a||la});
var oa="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},pa;
if("function"==typeof Object.setPrototypeOf)pa=Object.setPrototypeOf;else{var qa;a:{var ra={a:!0},sa={};try{sa.__proto__=ra;qa=sa.a;break a}catch(a){}qa=!1}pa=qa?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var ta=pa;
function v(a,b){a.prototype=oa(b.prototype);a.prototype.constructor=a;if(ta)ta(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.xa=b.prototype}
function ua(){this.v=!1;this.l=null;this.i=void 0;this.h=1;this.m=this.s=0;this.Ca=this.j=null}
function wa(a){if(a.v)throw new TypeError("Generator is already running");a.v=!0}
ua.prototype.ga=function(a){this.i=a};
function xa(a,b){a.j={exception:b,pd:!0};a.h=a.s||a.m}
ua.prototype.return=function(a){this.j={return:a};this.h=this.m};
ua.prototype.yield=function(a,b){this.h=b;return{value:a}};
ua.prototype.A=function(a){this.h=a};
function Aa(a,b,c){a.s=b;void 0!=c&&(a.m=c)}
function Ba(a,b){a.h=b;a.s=0}
function Ca(a){a.s=0;var b=a.j.exception;a.j=null;return b}
function Da(a){a.Ca=[a.j];a.s=0;a.m=0}
function Ea(a){var b=a.Ca.splice(0)[0];(b=a.j=a.j||b)?b.pd?a.h=a.s||a.m:void 0!=b.A&&a.m<b.A?(a.h=b.A,a.j=null):a.h=a.m:a.h=0}
function Fa(a){this.h=new ua;this.i=a}
function Ga(a,b){wa(a.h);var c=a.h.l;if(c)return Ha(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ia(a)}
function Ha(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.v=!1,e;var f=e.value}catch(g){return a.h.l=null,xa(a.h,g),Ia(a)}a.h.l=null;d.call(a.h,f);return Ia(a)}
function Ia(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.v=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,xa(a.h,c)}a.h.v=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.pd)throw b.exception;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ja(a){this.next=function(b){wa(a.h);a.h.l?b=Ha(a,a.h.l.next,b,a.h.ga):(a.h.ga(b),b=Ia(a));return b};
this.throw=function(b){wa(a.h);a.h.l?b=Ha(a,a.h.l["throw"],b,a.h.ga):(xa(a.h,b),b=Ia(a));return b};
this.return=function(b){return Ga(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ka(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function w(a){return Ka(new Ja(new Fa(a)))}
function Ma(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
n("Reflect.setPrototypeOf",function(a){return a?a:ta?function(b,c){try{return ta(b,c),!0}catch(d){return!1}}:null});
n("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.v=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(l){h.reject(l)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.m()})}this.h.push(g)};
var e=ea.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.m=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var l=g[h];g[h]=null;try{l()}catch(m){this.l(m)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(m){return function(p){l||(l=!0,m.call(h,p))}}
var h=this,l=!1;return{resolve:g(this.W),reject:g(this.m)}};
b.prototype.W=function(g){if(g===this)this.m(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.aa(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.T(g):this.s(g)}};
b.prototype.T=function(g){var h=void 0;try{h=g.then}catch(l){this.m(l);return}"function"==typeof h?this.da(h,g):this.s(g)};
b.prototype.m=function(g){this.ga(2,g)};
b.prototype.s=function(g){this.ga(1,g)};
b.prototype.ga=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.Z();this.Ca()};
b.prototype.Z=function(){var g=this;e(function(){if(g.M()){var h=ea.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.M=function(){if(this.v)return!1;var g=ea.CustomEvent,h=ea.Event,l=ea.dispatchEvent;if("undefined"===typeof l)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=ea.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return l(g)};
b.prototype.Ca=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.aa=function(g){var h=this.l();g.Yb(h.resolve,h.reject)};
b.prototype.da=function(g,h){var l=this.l();try{g.call(h,l.resolve,l.reject)}catch(m){l.reject(m)}};
b.prototype.then=function(g,h){function l(y,u){return"function"==typeof y?function(z){try{m(y(z))}catch(D){p(D)}}:u}
var m,p,r=new b(function(y,u){m=y;p=u});
this.Yb(l(g,m),l(h,p));return r};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Yb=function(g,h){function l(){switch(m.h){case 1:g(m.j);break;case 2:h(m.j);break;default:throw Error("Unexpected state: "+m.h);}}
var m=this;null==this.i?f.i(l):this.i.push(l);this.v=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,l){l(g)})};
b.race=function(g){return new b(function(h,l){for(var m=t(g),p=m.next();!p.done;p=m.next())d(p.value).Yb(h,l)})};
b.all=function(g){var h=t(g),l=h.next();return l.done?d([]):new b(function(m,p){function r(z){return function(D){y[z]=D;u--;0==u&&m(y)}}
var y=[],u=0;do y.push(void 0),u++,d(l.value).Yb(r(y.length-1),p),l=h.next();while(!l.done)})};
return b});
n("WeakMap",function(a){function b(l){this.h=(h+=Math.random()+1).toString();if(l){l=t(l);for(var m;!(m=l.next()).done;)m=m.value,this.set(m[0],m[1])}}
function c(){}
function d(l){var m=typeof l;return"object"===m&&null!==l||"function"===m}
function e(l){if(!ka(l,g)){var m=new c;ba(l,g,{value:m})}}
function f(l){var m=Object[l];m&&(Object[l]=function(p){if(p instanceof c)return p;Object.isExtensible(p)&&e(p);return m(p)})}
if(function(){if(!a||!Object.seal)return!1;try{var l=Object.seal({}),m=Object.seal({}),p=new a([[l,2],[m,3]]);if(2!=p.get(l)||3!=p.get(m))return!1;p.delete(l);p.set(m,4);return!p.has(l)&&4==p.get(m)}catch(r){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(l,m){if(!d(l))throw Error("Invalid WeakMap key");e(l);if(!ka(l,g))throw Error("WeakMap key fail: "+l);l[g][this.h]=m;return this};
b.prototype.get=function(l){return d(l)&&ka(l,g)?l[g][this.h]:void 0};
b.prototype.has=function(l){return d(l)&&ka(l,g)&&ka(l[g],this.h)};
b.prototype.delete=function(l){return d(l)&&ka(l,g)&&ka(l[g],this.h)?delete l[g][this.h]:!1};
return b});
n("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,l){var m=h.h;return fa(function(){if(m){for(;m.head!=h.h;)m=m.previous;for(;m.next!=m.head;)return m=m.next,{done:!1,value:l(m)};m=null}return{done:!0,value:void 0}})}
function d(h,l){var m=l&&typeof l;"object"==m||"function"==m?f.has(l)?m=f.get(l):(m=""+ ++g,f.set(l,m)):m="p_"+l;var p=h.data_[m];if(p&&ka(h.data_,m))for(h=0;h<p.length;h++){var r=p[h];if(l!==l&&r.key!==r.key||l===r.key)return{id:m,list:p,index:h,entry:r}}return{id:m,list:p,index:-1,entry:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=t(h);for(var l;!(l=h.next()).done;)l=l.value,this.set(l[0],l[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),l=new a(t([[h,"s"]]));if("s"!=l.get(h)||1!=l.size||l.get({x:4})||l.set({x:4},"t")!=l||2!=l.size)return!1;var m=l.entries(),p=m.next();if(p.done||p.value[0]!=h||"s"!=p.value[1])return!1;p=m.next();return p.done||4!=p.value[0].x||"t"!=p.value[1]||!m.next().done?!1:!0}catch(r){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,l){h=0===h?0:h;var m=d(this,h);m.list||(m.list=this.data_[m.id]=[]);m.entry?m.entry.value=l:(m.entry={next:this.h,previous:this.h.previous,head:this.h,key:h,value:l},m.list.push(m.entry),this.h.previous.next=m.entry,this.h.previous=m.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,l){for(var m=this.entries(),p;!(p=m.next()).done;)p=p.value,h.call(l,p[1],p[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Na(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
n("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Na(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
n("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
n("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Na(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
n("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
n("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
n("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
function Oa(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
n("Array.prototype.entries",function(a){return a?a:function(){return Oa(this,function(b,c){return[b,c]})}});
n("Array.prototype.keys",function(a){return a?a:function(){return Oa(this,function(b){return b})}});
n("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
n("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
n("Array.prototype.values",function(a){return a?a:function(){return Oa(this,function(b,c){return c})}});
n("Object.setPrototypeOf",function(a){return a||ta});
n("Set",function(a){function b(c){this.h=new Map;if(c){c=t(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(t([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
n("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ka(b,d)&&c.push([d,b[d]]);return c}});
n("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
n("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
n("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Na(this,b,"includes").indexOf(b,c||0)}});
n("globalThis",function(a){return a||ea});
n("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ka(b,d)&&c.push(b[d]);return c}});
var Pa=Pa||{},x=this||self;function A(a,b,c){a=a.split(".");c=c||x;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function B(a,b){a=a.split(".");b=b||x;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Qa(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Ra(a){var b=Qa(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Sa(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ta(a){return Object.prototype.hasOwnProperty.call(a,Ua)&&a[Ua]||(a[Ua]=++Va)}
var Ua="closure_uid_"+(1E9*Math.random()>>>0),Va=0;function Wa(a,b,c){return a.call.apply(a.bind,arguments)}
function Xa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Ya(a,b,c){Ya=Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Wa:Xa;return Ya.apply(null,arguments)}
function Za(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function $a(a,b){function c(){}
c.prototype=b.prototype;a.xa=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.base=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function ab(a){return a}
;function bb(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,bb);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
$a(bb,Error);bb.prototype.name="CustomError";function cb(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function db(){}
function eb(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var fb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},gb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},hb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},ib=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
gb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function jb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function kb(a,b){b=fb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function lb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ra(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function mb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function nb(a){var b=ob,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function pb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function qb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function rb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function sb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function tb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=tb(a[c]);return b}
var ub="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function vb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<ub.length;f++)c=ub[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var wb;function xb(){if(void 0===wb){var a=null,b=x.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:ab,createScript:ab,createScriptURL:ab})}catch(c){x.console&&x.console.error(c.message)}wb=a}else wb=a}return wb}
;function yb(a,b){this.j=a===zb&&b||""}
yb.prototype.i=!0;yb.prototype.h=function(){return this.j};
function Ab(a){return new yb(zb,a)}
var zb={};Ab("");var Bb={};function Cb(a){this.j=a;this.i=!0}
Cb.prototype.toString=function(){return this.j.toString()};
Cb.prototype.h=function(){return this.j.toString()};function Db(a){this.j=a}
Db.prototype.toString=function(){return this.j+""};
Db.prototype.i=!0;Db.prototype.h=function(){return this.j.toString()};
function Eb(a){if(a instanceof Db&&a.constructor===Db)return a.j;Qa(a);return"type_error:TrustedResourceUrl"}
var Fb={};function Gb(a){var b=xb();a=b?b.createScriptURL(a):a;return new Db(a,Fb)}
;var Hb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function Ib(a,b){return-1!=a.toLowerCase().indexOf(b.toLowerCase())}
function Jb(a,b){return a<b?-1:a>b?1:0}
;function Kb(a){this.j=a}
Kb.prototype.toString=function(){return this.j.toString()};
Kb.prototype.i=!0;Kb.prototype.h=function(){return this.j.toString()};
function Lb(a){if(a instanceof Kb&&a.constructor===Kb)return a.j;Qa(a);return"type_error:SafeUrl"}
var Mb;try{new URL("s://g"),Mb=!0}catch(a){Mb=!1}var Nb=Mb;function Ob(a){if(a instanceof Kb)return a;a="object"==typeof a&&a.i?a.h():String(a);a:{var b=a;if(Nb){try{var c=new URL(b)}catch(d){b="https:";break a}b=c.protocol}else b:{c=document.createElement("a");try{c.href=b}catch(d){b=void 0;break b}b=c.protocol;b=":"===b||""===b?"https:":b}}"javascript:"!==b||(a="about:invalid#zClosurez");return new Kb(a,Pb)}
var Pb={},Qb=new Kb("about:invalid#zClosurez",Pb);var Tb,Ub=B("CLOSURE_FLAGS"),Vb=Ub&&Ub[610401301];Tb=null!=Vb?Vb:!1;function Wb(){var a=x.navigator;return a&&(a=a.userAgent)?a:""}
var Xb,Yb=x.navigator;Xb=Yb?Yb.userAgentData||null:null;function Zb(a){return Tb?Xb?Xb.brands.some(function(b){return(b=b.brand)&&-1!=b.indexOf(a)}):!1:!1}
function C(a){return-1!=Wb().indexOf(a)}
;function $b(){return Tb?!!Xb&&0<Xb.brands.length:!1}
function ac(){return $b()?!1:C("Opera")}
function bc(){return $b()?!1:C("Trident")||C("MSIE")}
function cc(){return $b()?!1:C("Edge")}
function dc(){return $b()?Zb("Microsoft Edge"):C("Edg/")}
function ec(){return C("Firefox")||C("FxiOS")}
function fc(){return C("Safari")&&!(hc()||($b()?0:C("Coast"))||ac()||cc()||dc()||($b()?Zb("Opera"):C("OPR"))||ec()||C("Silk")||C("Android"))}
function hc(){return $b()?Zb("Chromium"):(C("Chrome")||C("CriOS"))&&!cc()||C("Silk")}
function ic(){return C("Android")&&!(hc()||ec()||ac()||C("Silk"))}
function jc(a){var b={};a.forEach(function(c){b[c[0]]=c[1]});
return function(c){return b[c.find(function(d){return d in b})]||""}}
function kc(a){var b=Wb();if("Internet Explorer"===a){if(bc())if((a=/rv: *([\d\.]*)/.exec(b))&&a[1])b=a[1];else{a="";var c=/MSIE +([\d\.]+)/.exec(b);if(c&&c[1])if(b=/Trident\/(\d.\d)/.exec(b),"7.0"==c[1])if(b&&b[1])switch(b[1]){case "4.0":a="8.0";break;case "5.0":a="9.0";break;case "6.0":a="10.0";break;case "7.0":a="11.0"}else a="7.0";else a=c[1];b=a}else b="";return b}var d=RegExp("([A-Z][\\w ]+)/([^\\s]+)\\s*(?:\\((.*?)\\))?","g");c=[];for(var e;e=d.exec(b);)c.push([e[1],e[2],e[3]||void 0]);b=jc(c);
switch(a){case "Opera":if(ac())return b(["Version","Opera"]);if($b()?Zb("Opera"):C("OPR"))return b(["OPR"]);break;case "Microsoft Edge":if(cc())return b(["Edge"]);if(dc())return b(["Edg"]);break;case "Chromium":if(hc())return b(["Chrome","CriOS","HeadlessChrome"])}return"Firefox"===a&&ec()||"Safari"===a&&fc()||"Android Browser"===a&&ic()||"Silk"===a&&C("Silk")?(b=c[2])&&b[1]||"":""}
function lc(a){if($b()&&"Silk"!==a){var b=Xb.brands.find(function(c){return c.brand===a});
if(!b||!b.version)return NaN;b=b.version.split(".")}else{b=kc(a);if(""===b)return NaN;b=b.split(".")}return 0===b.length?NaN:Number(b[0])}
;function mc(a){this.j=a;this.i=!0}
mc.prototype.h=function(){return this.j.toString()};
mc.prototype.toString=function(){return this.j.toString()};function nc(a,b){b=b instanceof Kb?b:Ob(b);a.href=Lb(b)}
function oc(a,b){a.rel="stylesheet";Ib("stylesheet","stylesheet")?(a.href=Eb(b).toString(),(b=pc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)):a.href=b instanceof Db?Eb(b).toString():b instanceof Kb?Lb(b):Lb(Ob(b))}
function rc(){return pc("script[nonce]")}
var sc=/^[\w+/_-]+[=]{0,2}$/;function pc(a,b){b=(b||x).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&sc.test(a)?a:"":""}
;function tc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var uc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function vc(a){return a?decodeURI(a):a}
function wc(a,b){return b.match(uc)[a]||null}
function xc(a){return vc(wc(3,a))}
function yc(a){var b=a.match(uc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function zc(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function Ac(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)Ac(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function Bc(a,b){var c=[];for(b=b||0;b<a.length;b+=2)Ac(a[b],a[b+1],c);return c.join("&")}
function Cc(a){var b=[],c;for(c in a)Ac(c,a[c],b);return b.join("&")}
function Dc(a,b){var c=2==arguments.length?Bc(arguments[1],0):Bc(arguments,1);return zc(a,c)}
function Ec(a,b){b=Cc(b);return zc(a,b)}
function Fc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return zc(a,b+c)}
function Gc(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var Hc=/#|$/,Ic=/[?&]($|#)/;function Jc(a,b){for(var c=a.search(Hc),d=0,e,f=[];0<=(e=Gc(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(Ic,"$1")}
;function Kc(a){x.setTimeout(function(){throw a;},0)}
;function Lc(){return Tb?!!Xb&&!!Xb.platform:!1}
function Mc(){return Lc()?"Android"===Xb.platform:C("Android")}
function Nc(){return C("iPhone")&&!C("iPod")&&!C("iPad")}
function Oc(){return Nc()||C("iPad")||C("iPod")}
function Pc(){return Lc()?"macOS"===Xb.platform:C("Macintosh")}
function Qc(){return Lc()?"Windows"===Xb.platform:C("Windows")}
function Rc(){return Lc()?"Chrome OS"===Xb.platform:C("CrOS")}
function Sc(){var a=Wb(),b="";Qc()?(b=/Windows (?:NT|Phone) ([0-9.]+)/,b=(a=b.exec(a))?a[1]:"0.0"):Oc()?(b=/(?:iPhone|iPod|iPad|CPU)\s+OS\s+(\S+)/,b=(a=b.exec(a))&&a[1].replace(/_/g,".")):Pc()?(b=/Mac OS X ([0-9_.]+)/,b=(a=b.exec(a))?a[1].replace(/_/g,"."):"10"):Ib(Wb(),"KaiOS")?(b=/(?:KaiOS)\/(\S+)/i,b=(a=b.exec(a))&&a[1]):Mc()?(b=/Android\s+([^\);]+)(\)|;)/,b=(a=b.exec(a))&&a[1]):Rc()&&(b=/(?:CrOS\s+(?:i686|x86_64)\s+([0-9.]+))/,b=(a=b.exec(a))&&a[1]);a=0;b=Hb(String(b||"")).split(".");for(var c=
Hb("12").split("."),d=Math.max(b.length,c.length),e=0;0==a&&e<d;e++){var f=b[e]||"",g=c[e]||"";do{f=/(\d*)(\D*)(.*)/.exec(f)||["","","",""];g=/(\d*)(\D*)(.*)/.exec(g)||["","","",""];if(0==f[0].length&&0==g[0].length)break;a=Jb(0==f[1].length?0:parseInt(f[1],10),0==g[1].length?0:parseInt(g[1],10))||Jb(0==f[2].length,0==g[2].length)||Jb(f[2],g[2]);f=f[3];g=g[3]}while(0==a)}}
;function Tc(a){Tc[" "](a);return a}
Tc[" "]=function(){};var Zc=ac(),$c=bc(),ad=C("Edge"),bd=C("Gecko")&&!(Ib(Wb(),"WebKit")&&!C("Edge"))&&!(C("Trident")||C("MSIE"))&&!C("Edge"),cd=Ib(Wb(),"WebKit")&&!C("Edge");cd&&C("Mobile");Pc();Qc();(Lc()?"Linux"===Xb.platform:C("Linux"))||Rc();var dd=x.navigator||null;dd&&(dd.appVersion||"").indexOf("X11");var ed=Mc();Nc();C("iPad");C("iPod");Oc();Ib(Wb(),"KaiOS");function fd(){var a=x.document;return a?a.documentMode:void 0}
var gd;a:{var hd="",id=function(){var a=Wb();if(bd)return/rv:([^\);]+)(\)|;)/.exec(a);if(ad)return/Edge\/([\d\.]+)/.exec(a);if($c)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(cd)return/WebKit\/(\S+)/.exec(a);if(Zc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
id&&(hd=id?id[1]:"");if($c){var jd=fd();if(null!=jd&&jd>parseFloat(hd)){gd=String(jd);break a}}gd=hd}var kd=gd,ld;if(x.document&&$c){var md=fd();ld=md?md:parseInt(kd,10)||void 0}else ld=void 0;var nd=ld;ec();var od=Nc()||C("iPod"),pd=C("iPad");ic();hc();var qd=fc()&&!Oc();var rd={},sd=null;
function td(a,b){Ra(a);void 0===b&&(b=0);if(!sd){sd={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));rd[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===sd[h]&&(sd[h]=g)}}}b=rd[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var l=a[f],m=a[f+1];h=a[f+2];g=b[l>>2];l=b[(l&3)<<4|m>>4];m=b[(m&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+l+m+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var ud="undefined"!==typeof Uint8Array,vd=!$c&&"function"===typeof btoa;var wd="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol():void 0;function xd(a,b){if(wd)return a[wd]|=b;if(void 0!==a.Ga)return a.Ga|=b;Object.defineProperties(a,{Ga:{value:b,configurable:!0,writable:!0,enumerable:!1}});return b}
function yd(a,b){wd?a[wd]&&(a[wd]&=~b):void 0!==a.Ga&&(a.Ga&=~b)}
function E(a){var b;wd?b=a[wd]:b=a.Ga;return null==b?0:b}
function zd(a,b){wd?a[wd]=b:void 0!==a.Ga?a.Ga=b:Object.defineProperties(a,{Ga:{value:b,configurable:!0,writable:!0,enumerable:!1}});return a}
function Ad(a,b){Object.isFrozen(a)&&(a=Array.prototype.slice.call(a));zd(a,b);return a}
function Bd(a){xd(a,1);return a}
function Cd(a,b){zd(b,(a|0)&-51)}
function Dd(a,b){zd(b,(a|18)&-41)}
;var Ed={};function Fd(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var Gd,Hd=Object.freeze(zd([],23));function Id(a){if(E(a.V)&2)throw Error();}
;function Jd(a){if(null!=a&&"number"!==typeof a)throw Error("Value of float/double field must be a number|null|undefined, found "+typeof a+": "+a);return a}
function Kd(a){return a.displayName||a.name||"unknown type name"}
function Ld(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Kd(b)+" but got "+(a&&Kd(a.constructor)));return a}
function Md(a,b,c){var d=!1;if(null!=a&&"object"===typeof a&&!(d=Array.isArray(a))&&a.Ic===Ed)return a;if(d){var e=d=E(a);0===e&&(e|=c&16);e|=c&2;e!==d&&zd(a,e);return new b(a)}}
;function Nd(a){var b=a.i+a.h;return a.Pa||(a.Pa=a.V[b]={})}
function Od(a,b,c){return-1===b?null:b>=a.i?a.Pa?a.Pa[b]:void 0:c&&a.Pa&&(c=a.Pa[b],null!=c)?c:a.V[b+a.h]}
function F(a,b,c){Id(a);return Td(a,b,c)}
function Td(a,b,c){a.j&&(a.j=void 0);if(b>=a.i)return Nd(a)[b]=c,a;a.V[b+a.h]=c;(c=a.Pa)&&b in c&&delete c[b];return a}
function Ud(a){return void 0!==Vd(a,Wd,11,!1)}
function Xd(a,b,c,d,e){d=Od(a,b,d);Array.isArray(d)||(d=Hd);var f=E(d);f&1||Bd(d);if(e)f&2||xd(d,18),c&1||Object.freeze(d);else{e=!(c&2);var g=f&2;c&1||!g?e&&f&16&&!g&&yd(d,16):(d=Bd(Array.prototype.slice.call(d)),Td(a,b,d))}return d}
function Yd(a,b,c,d){Id(a);(c=Zd(a,c))&&c!==b&&null!=d&&Td(a,c);return Td(a,b,d)}
function Zd(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=Od(a,e)&&(0!==c&&Td(a,c),c=e)}return c}
function Vd(a,b,c,d){d=Od(a,c,d);b=Md(d,b,E(a.V));b!==d&&null!=b&&Td(a,c,b);return b}
function $d(a,b,c,d){b=Vd(a,b,c,void 0===d?!1:d);if(null==b)return b;E(a.V)&2||(d=ae(b),d!==b&&(b=d,Td(a,c,b)));return b}
function be(a,b,c,d,e){var f=!!(e&2),g=Xd(a,c,1,void 0,f);if(g===Hd||!(E(g)&4)){var h=g;g=!!(e&2);var l=!!(E(h)&2);f=h;!g&&l&&(h=Array.prototype.slice.call(h));e|=l?2:0;for(var m=0,p=0;m<h.length;m++){var r=Md(h[m],b,e);void 0!==r&&(l=l||!!(2&E(r.V)),h[p++]=r)}p<m&&(h.length=p);b=h;e=!l;h=E(b);l=h|5;e=e?l|8:l&-9;h!=e&&(b=Ad(b,e));h=b;f!==h&&Td(a,c,h);(g||1===d)&&Object.freeze(h);return h}if(3===d)return g;f||(f=Object.isFrozen(g),1===d?f||Object.freeze(g):(d=E(g),b=d&-19,f&&(g=Array.prototype.slice.call(g),
d=0,Td(a,c,g)),d!==b&&zd(g,b)));return g}
function H(a,b,c,d){Id(a);null!=d?Ld(d,b):d=void 0;return Td(a,c,d)}
function ce(a,b,c,d,e){Id(a);null!=e?Ld(e,b):e=void 0;Yd(a,c,d,e)}
function de(a,b,c,d){Id(a);if(null!=d){for(var e=!!d.length,f=0;f<d.length;f++){var g=d[f];Ld(g,b);e=e&&!(E(g.V)&2)}b=E(d);f=b|1;f=(e?f|8:f&-9)|4;f!=b&&(d=Ad(d,f))}null==d&&(d=Hd);return Td(a,c,d)}
function ee(a,b,c,d){var e=E(a.V);if(e&2)throw Error();a=be(a,c,b,2,e);c=null!=d?Ld(d,c):new c;a.push(c);E(c.V)&2&&yd(a,8)}
function fe(a,b,c){Qa(c);F(a,b,c)}
function ge(){var a=new he;return F(a,1,1)}
function ie(a,b){return null==a?b:a}
function je(a,b){return ie(Od(a,b),"")}
;var ke;function le(a,b){return me(b)}
function me(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "boolean":return a?1:0;case "object":if(a&&!Array.isArray(a)&&ud&&null!=a&&a instanceof Uint8Array){if(vd){for(var b="",c=0,d=a.length-10240;c<d;)b+=String.fromCharCode.apply(null,a.subarray(c,c+=10240));b+=String.fromCharCode.apply(null,c?a.subarray(c):a);a=btoa(b)}else a=td(a);return a}}return a}
;function ne(a,b){var c=a.V,d=c.length,e=[];xd(e,16);var f=a.constructor.i,g=0;f&&(g=1,e.push(f));f=a.Pa;if(f){e.length=d;var h={};e[d-1]=h}var l=a.constructor;E(e);ke=e;l=new l(e);ke=void 0;a.od&&(l.od=a.od.slice());for(a=f?d-1:d;g<a;g++)e[g]=b(c[g]);if(f)for(var m in f)h[m]=b(f[m]);return l}
function oe(a,b,c,d,e,f){if(null!=a){if(Array.isArray(a))a=e&&0==a.length&&E(a)&1?void 0:f&&E(a)&2?a:pe(a,b,c,void 0!==d,e,f);else if(Fd(a)){var g={},h;for(h in a)g[h]=oe(a[h],b,c,d,e,f);a=g}else a=b(a,d);return a}}
function pe(a,b,c,d,e,f){var g=d||c?E(a):0;d=d?!!(g&16):void 0;a=Array.prototype.slice.call(a);for(var h=0;h<a.length;h++)a[h]=oe(a[h],b,c,d,e,f);c&&c(g,a);return a}
function qe(a){return a.Ic===Ed?a.toJSON():me(a)}
;function re(a,b,c){c=void 0===c?Dd:c;if(null!=a){if(ud&&a instanceof Uint8Array)return b?a:new Uint8Array(a);if(Array.isArray(a)){var d=E(a);if(d&2)return a;if(b&&!(d&32)&&(d&16||0===d))return zd(a,d|18),a;a=pe(a,re,d&4?Dd:c,!0,!1,!0);b=E(a);b&4&&b&2&&Object.freeze(a);return a}a.Ic===Ed&&(E(a.V)&2||(a=se(a,!0),xd(a.V,18)));return a}}
function se(a,b){var c=a.V,d=b||E(a.V)&2?Dd:Cd,e=!!(E(c)&16);return ne(a,function(f){return re(f,e,d)})}
function ae(a){if(!(E(a.V)&2))return a;var b=se(a,!1);b.j=a;return b}
;function I(a,b,c,d){null==a&&(a=ke);ke=void 0;if(null==a){a=d?[d]:[];var e=!0;zd(a,48)}else{if(!Array.isArray(a))throw Error();if(d&&d!==a[0])throw Error();var f=xd(a,0)|32;e=0!==(16&f);zd(a,f)}this.h=d?0:-1;this.V=a;a:{f=this.V.length;d=f-1;if(f&&(f=this.V[d],Fd(f))){this.Pa=f;this.i=d-this.h;break a}b?(this.i=Math.max(b,d+1-this.h),this.Pa=void 0):this.i=Number.MAX_VALUE}if(c){b=e&&!0;e=this.i;var g;for(d=0;d<c.length;d++)if(f=c[d],f<e){f+=this.h;var h=a[f];h?te(h,b):a[f]=Hd}else g||(g=Nd(this)),
(h=g[f])?te(h,b):g[f]=Hd}E(this.V)}
k=I.prototype;k.toJSON=function(){var a=this.V,b;Gd?b=a:b=pe(a,qe,void 0,void 0,!1,!1);return b};
k.serialize=function(){Gd=!0;try{return JSON.stringify(this.toJSON(),le)}finally{Gd=!1}};
k.clone=function(){return se(this,!1)};
function te(a,b){if(Array.isArray(a)){var c=E(a),d=1;!b||c&2||(d|=16);(c&d)!==d&&zd(a,c|d)}}
k.Ic=Ed;k.toString=function(){return this.V.toString()};function ue(a){this.bd=a}
;function ve(a,b,c){this.i=a;this.l=b;this.h=c||[];this.rb=new Map}
k=ve.prototype;k.Td=function(a){var b=Ma.apply(1,arguments),c=this.xc(b);c?c.push(new ue(a)):this.Cd(a,b)};
k.Cd=function(a){var b=this.gd(Ma.apply(1,arguments));this.rb.set(b,[new ue(a)])};
k.xc=function(){var a=this.gd(Ma.apply(0,arguments));return this.rb.has(a)?this.rb.get(a):void 0};
k.ke=function(){var a=this.xc(Ma.apply(0,arguments));return a&&a.length?a[0]:void 0};
k.clear=function(){this.rb.clear()};
k.gd=function(){var a=Ma.apply(0,arguments);return a?a.join(","):"key"};function we(a,b){ve.call(this,a,3,b)}
v(we,ve);we.prototype.j=function(a){var b=Ma.apply(1,arguments),c=0,d=this.ke(b);d&&(c=d.bd);this.Cd(c+a,b)};function xe(a,b){ve.call(this,a,2,b)}
v(xe,ve);xe.prototype.record=function(a){this.Td(a,Ma.apply(1,arguments))};function ye(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function ze(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Ra(d)?ze.apply(null,d):ye(d)}}
;function J(){this.Ca=this.Ca;this.ga=this.ga}
J.prototype.Ca=!1;J.prototype.h=function(){return this.Ca};
J.prototype.dispose=function(){this.Ca||(this.Ca=!0,this.K())};
function Ae(a,b){Be(a,Za(ye,b))}
function Be(a,b){a.Ca?b():(a.ga||(a.ga=[]),a.ga.push(b))}
J.prototype.K=function(){if(this.ga)for(;this.ga.length;)this.ga.shift()()};function Ce(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Ce.prototype.stopPropagation=function(){this.j=!0};
Ce.prototype.preventDefault=function(){this.defaultPrevented=!0};function De(a){var b=B("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||x.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Ee(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Fe[c])c=Fe[c];else{c=String(c);if(!Fe[c]){var f=/function\s+([^\(]+)/m.exec(c);Fe[c]=f?f[1]:"[Anonymous]"}c=Fe[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function Ee(a,b){b||(b={});b[Ge(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[Ge(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=Ee(a,b));return c}
function Ge(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var Fe={};var He=function(){if(!x.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{var c=function(){};
x.addEventListener("test",c,b);x.removeEventListener("test",c,b)}catch(d){}return a}();function Ie(a,b){Ce.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
$a(Ie,Ce);var Je={2:"touch",3:"pen",4:"mouse"};
Ie.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(bd){a:{try{Tc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Je[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&Ie.xa.preventDefault.call(this)};
Ie.prototype.stopPropagation=function(){Ie.xa.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
Ie.prototype.preventDefault=function(){Ie.xa.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var Ke="closure_listenable_"+(1E6*Math.random()|0);var Le=0;function Me(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.dc=e;this.key=++Le;this.Nb=this.Xb=!1}
function Ne(a){a.Nb=!0;a.listener=null;a.proxy=null;a.src=null;a.dc=null}
;function Oe(a){this.src=a;this.listeners={};this.h=0}
Oe.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Pe(a,b,d,e);-1<g?(b=a[g],c||(b.Xb=!1)):(b=new Me(b,this.src,f,!!d,e),b.Xb=c,a.push(b));return b};
Oe.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Pe(e,b,c,d);return-1<b?(Ne(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function Qe(a,b){var c=b.type;c in a.listeners&&kb(a.listeners[c],b)&&(Ne(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function Pe(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Nb&&f.listener==b&&f.capture==!!c&&f.dc==d)return e}return-1}
;var Re="closure_lm_"+(1E6*Math.random()|0),Se={},Te=0;function Ue(a,b,c,d,e){if(d&&d.once)Ve(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Ue(a,b[f],c,d,e);else c=We(c),a&&a[Ke]?a.listen(b,c,Sa(d)?!!d.capture:!!d,e):Xe(a,b,c,!1,d,e)}
function Xe(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Sa(e)?!!e.capture:!!e,h=Ye(a);h||(a[Re]=h=new Oe(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Ze();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)He||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent($e(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Te++}}
function Ze(){function a(c){return b.call(a.src,a.listener,c)}
var b=af;return a}
function Ve(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ve(a,b[f],c,d,e);else c=We(c),a&&a[Ke]?a.l.add(String(b),c,!0,Sa(d)?!!d.capture:!!d,e):Xe(a,b,c,!0,d,e)}
function bf(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)bf(a,b[f],c,d,e);else(d=Sa(d)?!!d.capture:!!d,c=We(c),a&&a[Ke])?a.l.remove(String(b),c,d,e):a&&(a=Ye(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Pe(b,c,d,e)),(c=-1<a?b[a]:null)&&cf(c))}
function cf(a){if("number"!==typeof a&&a&&!a.Nb){var b=a.src;if(b&&b[Ke])Qe(b.l,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent($e(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Te--;(c=Ye(b))?(Qe(c,a),0==c.h&&(c.src=null,b[Re]=null)):Ne(a)}}}
function $e(a){return a in Se?Se[a]:Se[a]="on"+a}
function af(a,b){if(a.Nb)a=!0;else{b=new Ie(b,this);var c=a.listener,d=a.dc||a.src;a.Xb&&cf(a);a=c.call(d,b)}return a}
function Ye(a){a=a[Re];return a instanceof Oe?a:null}
var df="__closure_events_fn_"+(1E9*Math.random()>>>0);function We(a){if("function"===typeof a)return a;a[df]||(a[df]=function(b){return a.handleEvent(b)});
return a[df]}
;function ef(){J.call(this);this.l=new Oe(this);this.Pd=this;this.Da=null}
$a(ef,J);ef.prototype[Ke]=!0;k=ef.prototype;k.addEventListener=function(a,b,c,d){Ue(this,a,b,c,d)};
k.removeEventListener=function(a,b,c,d){bf(this,a,b,c,d)};
function ff(a,b){var c=a.Da;if(c){var d=[];for(var e=1;c;c=c.Da)d.push(c),++e}a=a.Pd;c=b.type||b;"string"===typeof b?b=new Ce(b,a):b instanceof Ce?b.target=b.target||a:(e=b,b=new Ce(c,a),vb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=gf(g,c,!0,b)&&e}b.j||(g=b.h=a,e=gf(g,c,!0,b)&&e,b.j||(e=gf(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=gf(g,c,!1,b)&&e}
k.K=function(){ef.xa.K.call(this);this.removeAllListeners();this.Da=null};
k.listen=function(a,b,c,d){return this.l.add(String(a),b,!1,c,d)};
k.removeAllListeners=function(a){if(this.l){var b=this.l;a=a&&a.toString();var c=0,d;for(d in b.listeners)if(!a||d==a){for(var e=b.listeners[d],f=0;f<e.length;f++)++c,Ne(e[f]);delete b.listeners[d];b.h--}b=c}else b=0;return b};
function gf(a,b,c,d){b=a.l.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Nb&&g.capture==c){var h=g.listener,l=g.dc||g.src;g.Xb&&Qe(a.l,g);e=!1!==h.call(l,d)&&e}}return e&&!d.defaultPrevented}
;function hf(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
hf.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function of(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;function pf(a,b){return a+Math.random()*(b-a)}
;function qf(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
k=qf.prototype;k.clone=function(){return new qf(this.x,this.y)};
k.equals=function(a){return a instanceof qf&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
k.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
k.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
k.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
k.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function rf(a,b){this.width=a;this.height=b}
k=rf.prototype;k.clone=function(){return new rf(this.width,this.height)};
k.aspectRatio=function(){return this.width/this.height};
k.isEmpty=function(){return!(this.width*this.height)};
k.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
k.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
k.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
k.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function sf(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function tf(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function uf(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var vf;function wf(){var a=x.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!C("Presto")&&(a=function(){var e=tf("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Ya(function(l){if(("*"==h||l.origin==h)&&l.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!bc()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.Zc;c.Zc=null;e()}};
return function(e){d.next={Zc:e};d=d.next;b.port2.postMessage(0)}}return function(e){x.setTimeout(e,0)}}
;function xf(){this.i=this.h=null}
xf.prototype.add=function(a,b){var c=yf.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
xf.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var yf=new hf(function(){return new zf},function(a){return a.reset()});
function zf(){this.next=this.scope=this.fn=null}
zf.prototype.set=function(a,b){this.fn=a;this.scope=b;this.next=null};
zf.prototype.reset=function(){this.next=this.scope=this.fn=null};var Af,Bf=!1,Cf=new xf;function Df(a,b){Af||Ef();Bf||(Af(),Bf=!0);Cf.add(a,b)}
function Ef(){if(x.Promise&&x.Promise.resolve){var a=x.Promise.resolve(void 0);Af=function(){a.then(Ff)}}else Af=function(){var b=Ff;
"function"!==typeof x.setImmediate||x.Window&&x.Window.prototype&&!cc()&&x.Window.prototype.setImmediate==x.setImmediate?(vf||(vf=wf()),vf(b)):x.setImmediate(b)}}
function Ff(){for(var a;a=Cf.remove();){try{a.fn.call(a.scope)}catch(b){Kc(b)}of(yf,a)}Bf=!1}
;function Gf(a){this.h=0;this.v=void 0;this.l=this.i=this.j=null;this.m=this.s=!1;if(a!=db)try{var b=this;a.call(void 0,function(c){Hf(b,2,c)},function(c){Hf(b,3,c)})}catch(c){Hf(this,3,c)}}
function If(){this.next=this.context=this.h=this.i=this.child=null;this.j=!1}
If.prototype.reset=function(){this.context=this.h=this.i=this.child=null;this.j=!1};
var Jf=new hf(function(){return new If},function(a){a.reset()});
function Kf(a,b,c){var d=Jf.get();d.i=a;d.h=b;d.context=c;return d}
function Lf(a){if(a instanceof Gf)return a;var b=new Gf(db);Hf(b,2,a);return b}
function Mf(a){return new Gf(function(b,c){c(a)})}
function Nf(a,b,c){Of(a,b,c,null)||Df(Za(b,a))}
function Pf(a){return new Gf(function(b){var c=a.length,d=[];if(c)for(var e=function(h,l,m){c--;d[h]=l?{fulfilled:!0,value:m}:{fulfilled:!1,reason:m};0==c&&b(d)},f=0,g;f<a.length;f++)g=a[f],Nf(g,Za(e,f,!0),Za(e,f,!1));
else b(d)})}
Gf.prototype.then=function(a,b,c){return Qf(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Gf.prototype.$goog_Thenable=!0;k=Gf.prototype;k.oc=function(a,b){return Qf(this,null,a,b)};
k.catch=Gf.prototype.oc;k.cancel=function(a){if(0==this.h){var b=new Rf(a);Df(function(){Sf(this,b)},this)}};
function Sf(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.child==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?Sf(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):Tf(c),Uf(c,e,3,b)))}a.j=null}else Hf(a,3,b)}
function Vf(a,b){a.i||2!=a.h&&3!=a.h||Wf(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Qf(a,b,c,d){var e=Kf(null,null,null);e.child=new Gf(function(f,g){e.i=b?function(h){try{var l=b.call(d,h);f(l)}catch(m){g(m)}}:f;
e.h=c?function(h){try{var l=c.call(d,h);void 0===l&&h instanceof Rf?g(h):f(l)}catch(m){g(m)}}:g});
e.child.j=a;Vf(a,e);return e.child}
k.Ye=function(a){this.h=0;Hf(this,2,a)};
k.Ze=function(a){this.h=0;Hf(this,3,a)};
function Hf(a,b,c){0==a.h&&(a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself")),a.h=1,Of(c,a.Ye,a.Ze,a)||(a.v=c,a.h=b,a.j=null,Wf(a),3!=b||c instanceof Rf||Xf(a,c)))}
function Of(a,b,c,d){if(a instanceof Gf)return Vf(a,Kf(b||db,c||null,d)),!0;if(a)try{var e=!!a.$goog_Thenable}catch(g){e=!1}else e=!1;if(e)return a.then(b,c,d),!0;if(Sa(a))try{var f=a.then;if("function"===typeof f)return Yf(a,f,b,c,d),!0}catch(g){return c.call(d,g),!0}return!1}
function Yf(a,b,c,d,e){function f(l){h||(h=!0,d.call(e,l))}
function g(l){h||(h=!0,c.call(e,l))}
var h=!1;try{b.call(a,g,f)}catch(l){f(l)}}
function Wf(a){a.s||(a.s=!0,Df(a.de,a))}
function Tf(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
k.de=function(){for(var a;a=Tf(this);)Uf(this,a,this.h,this.v);this.s=!1};
function Uf(a,b,c,d){if(3==c&&b.h&&!b.j)for(;a&&a.m;a=a.j)a.m=!1;if(b.child)b.child.j=null,Zf(b,c,d);else try{b.j?b.i.call(b.context):Zf(b,c,d)}catch(e){$f.call(null,e)}of(Jf,b)}
function Zf(a,b,c){2==b?a.i.call(a.context,c):a.h&&a.h.call(a.context,c)}
function Xf(a,b){a.m=!0;Df(function(){a.m&&$f.call(null,b)})}
var $f=Kc;function Rf(a){bb.call(this,a)}
$a(Rf,bb);Rf.prototype.name="cancel";function ag(a,b){ef.call(this);this.j=a||1;this.i=b||x;this.m=Ya(this.Xe,this);this.s=Date.now()}
$a(ag,ef);k=ag.prototype;k.enabled=!1;k.Ba=null;k.setInterval=function(a){this.j=a;this.Ba&&this.enabled?(this.stop(),this.start()):this.Ba&&this.stop()};
k.Xe=function(){if(this.enabled){var a=Date.now()-this.s;0<a&&a<.8*this.j?this.Ba=this.i.setTimeout(this.m,this.j-a):(this.Ba&&(this.i.clearTimeout(this.Ba),this.Ba=null),ff(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
k.start=function(){this.enabled=!0;this.Ba||(this.Ba=this.i.setTimeout(this.m,this.j),this.s=Date.now())};
k.stop=function(){this.enabled=!1;this.Ba&&(this.i.clearTimeout(this.Ba),this.Ba=null)};
k.K=function(){ag.xa.K.call(this);this.stop();delete this.i};
function bg(a,b,c){if("function"===typeof a)c&&(a=Ya(a,c));else if(a&&"function"==typeof a.handleEvent)a=Ya(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:x.setTimeout(a,b||0)}
;function cg(a){J.call(this);this.M=a;this.j=new Map;this.v=new Set;this.l=0;this.m=100;this.flushInterval=3E4;this.i=new ag(this.flushInterval);this.i.listen("tick",this.ob,!1,this);Ae(this,this.i);this.s=!1}
v(cg,J);k=cg.prototype;k.sendIsolatedPayload=function(a){this.s=a;this.m=1};
function dg(a){a.i.enabled||a.i.start();a.l++;a.l>=a.m&&a.ob()}
k.ob=function(){var a=this.j.values();a=[].concat(ia(a)).filter(function(b){return b.rb.size});
a.length&&this.M.flush(a,this.s);eg(a);this.l=0;this.i.enabled&&this.i.stop()};
k.Vc=function(a){var b=Ma.apply(1,arguments);this.j.has(a)||this.j.set(a,new we(a,b))};
k.Wc=function(a){var b=Ma.apply(1,arguments);this.j.has(a)||this.j.set(a,new xe(a,b))};
function fg(a,b){return a.v.has(b)?void 0:a.j.get(b)}
k.pc=function(a){this.Od.apply(this,[a,1].concat(ia(Ma.apply(1,arguments))))};
k.Od=function(a,b){var c=Ma.apply(2,arguments),d=fg(this,a);d&&d instanceof we&&(d.j(b,c),dg(this))};
k.record=function(a,b){var c=Ma.apply(2,arguments),d=fg(this,a);d&&d instanceof xe&&(d.record(b,c),dg(this))};
function eg(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function gg(a){this.h=a;this.h.Vc("/client_streamz/bg/fiec",{Kb:3,Jb:"rk"},{Kb:2,Jb:"ec"})}
function hg(a,b,c){a.h.pc("/client_streamz/bg/fiec",b,c)}
function ig(a){this.h=a;this.h.Wc("/client_streamz/bg/fil",{Kb:3,Jb:"rk"})}
ig.prototype.record=function(a,b){this.h.record("/client_streamz/bg/fil",a,b)};
function jg(a){this.h=a;this.h.Vc("/client_streamz/bg/fsc",{Kb:3,Jb:"rk"})}
function kg(a){this.h=a;this.h.Wc("/client_streamz/bg/fsl",{Kb:3,Jb:"rk"})}
kg.prototype.record=function(a,b){this.h.record("/client_streamz/bg/fsl",a,b)};var lg={toString:function(a){var b=[],c=0;a-=-2147483648;b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ".charAt(a%52);for(a=Math.floor(a/52);0<a;)b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789".charAt(a%62),a=Math.floor(a/62);return b.join("")}};function mg(a){function b(){c-=d;c-=e;c^=e>>>13;d-=e;d-=c;d^=c<<8;e-=c;e-=d;e^=d>>>13;c-=d;c-=e;c^=e>>>12;d-=e;d-=c;d^=c<<16;e-=c;e-=d;e^=d>>>5;c-=d;c-=e;c^=e>>>3;d-=e;d-=c;d^=c<<10;e-=c;e-=d;e^=d>>>15}
a=ng(a);for(var c=2654435769,d=2654435769,e=314159265,f=a.length,g=f,h=0;12<=g;g-=12,h+=12)c+=og(a,h),d+=og(a,h+4),e+=og(a,h+8),b();e+=f;switch(g){case 11:e+=a[h+10]<<24;case 10:e+=a[h+9]<<16;case 9:e+=a[h+8]<<8;case 8:d+=a[h+7]<<24;case 7:d+=a[h+6]<<16;case 6:d+=a[h+5]<<8;case 5:d+=a[h+4];case 4:c+=a[h+3]<<24;case 3:c+=a[h+2]<<16;case 2:c+=a[h+1]<<8;case 1:c+=a[h+0]}b();return lg.toString(e)}
function ng(a){for(var b=[],c=0;c<a.length;c++)b.push(a.charCodeAt(c));return b}
function og(a,b){return a[b+0]+(a[b+1]<<8)+(a[b+2]<<16)+(a[b+3]<<24)}
;function pg(a){I.call(this,a)}
v(pg,I);var qg=[1,2,3];function rg(a){I.call(this,a)}
v(rg,I);var sg=[1,2,3];function tg(a){I.call(this,a,0,tg.h)}
v(tg,I);tg.h=[1];function ug(a){I.call(this,a,0,ug.h)}
v(ug,I);ug.h=[3,6,4];function vg(a){I.call(this,a,0,vg.h)}
v(vg,I);vg.h=[1];function wg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a.startsWith("blob:")&&(a=a.substring(5));a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==
c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function xg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;p=m=0}
function b(r){for(var y=g,u=0;64>u;u+=4)y[u/4]=r[u]<<24|r[u+1]<<16|r[u+2]<<8|r[u+3];for(u=16;80>u;u++)r=y[u-3]^y[u-8]^y[u-14]^y[u-16],y[u]=(r<<1|r>>>31)&4294967295;r=e[0];var z=e[1],D=e[2],G=e[3],M=e[4];for(u=0;80>u;u++){if(40>u)if(20>u){var P=G^z&(D^G);var T=1518500249}else P=z^D^G,T=1859775393;else 60>u?(P=z&D|G&(z|D),T=2400959708):(P=z^D^G,T=3395469782);P=((r<<5|r>>>27)&4294967295)+P+M+T+y[u]&4294967295;M=G;G=D;D=(z<<30|z>>>2)&4294967295;z=r;r=P}e[0]=e[0]+r&4294967295;e[1]=e[1]+z&4294967295;e[2]=
e[2]+D&4294967295;e[3]=e[3]+G&4294967295;e[4]=e[4]+M&4294967295}
function c(r,y){if("string"===typeof r){r=unescape(encodeURIComponent(r));for(var u=[],z=0,D=r.length;z<D;++z)u.push(r.charCodeAt(z));r=u}y||(y=r.length);u=0;if(0==m)for(;u+64<y;)b(r.slice(u,u+64)),u+=64,p+=64;for(;u<y;)if(f[m++]=r[u++],p++,64==m)for(m=0,b(f);u+64<y;)b(r.slice(u,u+64)),u+=64,p+=64}
function d(){var r=[],y=8*p;56>m?c(h,56-m):c(h,64-(m-56));for(var u=63;56<=u;u--)f[u]=y&255,y>>>=8;b(f);for(u=y=0;5>u;u++)for(var z=24;0<=z;z-=8)r[y++]=e[u]>>z&255;return r}
for(var e=[],f=[],g=[],h=[128],l=1;64>l;++l)h[l]=0;var m,p;a();return{reset:a,update:c,digest:d,Zd:function(){for(var r=d(),y="",u=0;u<r.length;u++)y+="0123456789ABCDEF".charAt(Math.floor(r[u]/16))+"0123456789ABCDEF".charAt(r[u]%16);return y}}}
;function yg(a,b,c){var d=String(x.location.href);return d&&a&&b?[b,zg(wg(d),a,c||null)].join(" "):null}
function zg(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],gb(d,function(h){e.push(h)}),Ag(e.join(" "));
var f=[],g=[];gb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];gb(d,function(h){e.push(h)});
a=Ag(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function Ag(a){var b=xg();b.update(a);return b.Zd().toLowerCase()}
;var Bg={};function Cg(a){this.h=a||{cookie:""}}
k=Cg.prototype;k.isEnabled=function(){if(!x.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{hc:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
k.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Mf;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.hc}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
k.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Hb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
k.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{hc:0,path:b,domain:c});return d};
k.Ac=function(){return Dg(this).keys};
k.isEmpty=function(){return!this.h.cookie};
k.clear=function(){for(var a=Dg(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function Dg(a){a=(a.h.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Hb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var Eg=new Cg("undefined"==typeof document?null:document);function Fg(a){return!!Bg.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function Gg(a){a=void 0===a?!1:a;var b=x.__SAPISID||x.__APISID||x.__3PSAPISID||x.__OVERRIDE_SID;Fg(a)&&(b=b||x.__1PSAPISID);if(b)return!0;if("undefined"!==typeof document){var c=new Cg(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID")||c.get("OSID");Fg(a)&&(b=b||c.get("__Secure-1PAPISID"))}return!!b}
function Hg(a,b,c,d){(a=x[a])||"undefined"===typeof document||(a=(new Cg(document)).get(b));return a?yg(a,c,d):null}
function Ig(a,b){b=void 0===b?!1:b;var c=wg(String(x.location.href)),d=[];if(Gg(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?x.__SAPISID:x.__APISID;e||"undefined"===typeof document||(e=new Cg(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?yg(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&Fg(b)&&((b=Hg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=Hg("__3PSAPISID","__Secure-3PAPISID",
"SAPISID3PHASH",a))&&d.push(a))}return 0==d.length?null:d.join(" ")}
;function Jg(a){I.call(this,a,0,Jg.h)}
v(Jg,I);Jg.h=[2];function Kg(a){this.h=this.i=this.j=a}
Kg.prototype.reset=function(){this.h=this.i=this.j};
Kg.prototype.getValue=function(){return this.i};function Lg(){}
Lg.prototype.serialize=function(a){var b=[];Mg(this,a,b);return b.join("")};
function Mg(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Mg(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),Ng(d,c),c.push(":"),Mg(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Ng(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Og={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},Pg=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Ng(a,b){b.push('"',a.replace(Pg,function(c){var d=Og[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),Og[c]=d);return d}),'"')}
;function Qg(){}
Qg.prototype.h=null;Qg.prototype.getOptions=function(){var a;(a=this.h)||(a={},Rg(this)&&(a[0]=!0,a[1]=!0),a=this.h=a);return a};var Sg;function Tg(){}
$a(Tg,Qg);function Ug(a){return(a=Rg(a))?new ActiveXObject(a):new XMLHttpRequest}
function Rg(a){if(!a.i&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.i=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.i}
Sg=new Tg;function Vg(a){ef.call(this);this.headers=new Map;this.W=a||null;this.i=!1;this.T=this.G=null;this.m=this.da="";this.j=this.aa=this.v=this.Z=!1;this.s=0;this.M=null;this.ya="";this.ka=this.la=!1}
$a(Vg,ef);var Wg=/^https?$/i,Xg=["POST","PUT"],Yg=[];function Zg(a,b,c,d,e,f,g){var h=new Vg;Yg.push(h);b&&h.listen("complete",b);h.l.add("ready",h.Yd,!0,void 0,void 0);f&&(h.s=Math.max(0,f));g&&(h.la=g);h.send(a,c,d,e)}
k=Vg.prototype;k.Yd=function(){this.dispose();kb(Yg,this)};
k.send=function(a,b,c,d){if(this.G)throw Error("[goog.net.XhrIo] Object is active with another request="+this.da+"; newUri="+a);b=b?b.toUpperCase():"GET";this.da=a;this.m="";this.Z=!1;this.i=!0;this.G=this.W?Ug(this.W):Ug(Sg);this.T=this.W?this.W.getOptions():Sg.getOptions();this.G.onreadystatechange=Ya(this.td,this);try{this.getStatus(),this.aa=!0,this.G.open(b,String(a),!0),this.aa=!1}catch(g){this.getStatus();$g(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===
Object.prototype)for(var e in d)c.set(e,d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=t(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=x.FormData&&a instanceof x.FormData;!(0<=fb(Xg,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=t(c);for(d=b.next();!d.done;d=b.next())c=t(d.value),d=c.next().value,c=c.next().value,this.G.setRequestHeader(d,c);this.ya&&(this.G.responseType=this.ya);"withCredentials"in this.G&&this.G.withCredentials!==this.la&&(this.G.withCredentials=this.la);try{ah(this),0<this.s&&(this.ka=bh(this.G),this.getStatus(),this.ka?(this.G.timeout=this.s,this.G.ontimeout=Ya(this.Hd,
this)):this.M=bg(this.Hd,this.s,this)),this.getStatus(),this.v=!0,this.G.send(a),this.v=!1}catch(g){this.getStatus(),$g(this,g)}};
function bh(a){return $c&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
k.Hd=function(){"undefined"!=typeof Pa&&this.G&&(this.m="Timed out after "+this.s+"ms, aborting",this.getStatus(),ff(this,"timeout"),this.abort(8))};
function $g(a,b){a.i=!1;a.G&&(a.j=!0,a.G.abort(),a.j=!1);a.m=b;ch(a);dh(a)}
function ch(a){a.Z||(a.Z=!0,ff(a,"complete"),ff(a,"error"))}
k.abort=function(){this.G&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.G.abort(),this.j=!1,ff(this,"complete"),ff(this,"abort"),dh(this))};
k.K=function(){this.G&&(this.i&&(this.i=!1,this.j=!0,this.G.abort(),this.j=!1),dh(this,!0));Vg.xa.K.call(this)};
k.td=function(){this.h()||(this.aa||this.v||this.j?eh(this):this.Ae())};
k.Ae=function(){eh(this)};
function eh(a){if(a.i&&"undefined"!=typeof Pa)if(a.T[1]&&4==fh(a)&&2==a.getStatus())a.getStatus();else if(a.v&&4==fh(a))bg(a.td,0,a);else if(ff(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if(gh(a))ff(a,"complete"),ff(a,"success");else{try{var b=2<fh(a)?a.G.statusText:""}catch(c){b=""}a.m=b+" ["+a.getStatus()+"]";ch(a)}}finally{dh(a)}}}
function dh(a,b){if(a.G){ah(a);var c=a.G,d=a.T[0]?function(){}:null;
a.G=null;a.T=null;b||ff(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function ah(a){a.G&&a.ka&&(a.G.ontimeout=null);a.M&&(x.clearTimeout(a.M),a.M=null)}
k.isActive=function(){return!!this.G};
k.isComplete=function(){return 4==fh(this)};
function gh(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=wc(1,String(a.da)),!a&&x.self&&x.self.location&&(a=x.self.location.protocol.slice(0,-1)),b=!Wg.test(a?a.toLowerCase():"");c=b}return c}
function fh(a){return a.G?a.G.readyState:0}
k.getStatus=function(){try{return 2<fh(this)?this.G.status:-1}catch(a){return-1}};
k.getLastError=function(){return"string"===typeof this.m?this.m:String(this.m)};function hh(a){I.call(this,a)}
v(hh,I);function ih(a){I.call(this,a,0,ih.h)}
v(ih,I);ih.h=[1];function Wd(a){I.call(this,a)}
v(Wd,I);var jh=["platform","platformVersion","architecture","model","uaFullVersion"];new ih;function he(a){I.call(this,a)}
v(he,I);function kh(a){I.call(this,a,33,kh.h)}
v(kh,I);kh.h=[3,20,27];function lh(a){I.call(this,a,19,lh.h)}
v(lh,I);lh.h=[3,5];function mh(a){I.call(this,a,6,mh.h)}
v(mh,I);mh.h=[5];function nh(a){I.call(this,a)}
v(nh,I);var oh;oh=new function(a,b,c){this.h=a;this.fieldName=b;this.ctor=c;this.isRepeated=0;this.i=$d;this.defaultValue=void 0}(175237375,{Ef:0},nh);function ph(a,b,c,d,e,f,g,h,l,m,p){ef.call(this);var r=this;this.componentId="";this.j=[];this.Tb="";this.Ub=this.ya=-1;this.Fb=!1;this.W=this.m=null;this.M=this.T=0;this.Rd=1;this.timeoutMillis=0;this.la=!1;ef.call(this);this.logSource=a;this.Sb=b||function(){};
this.s=new qh(a,f);this.Qd=d;this.network=p;this.bufferSize=1E3;this.Sd=Za(pf,0,1);this.aa=e||null;this.sessionIndex=c||null;this.da=g||!1;this.pageId=l||null;this.logger=null;this.withCredentials=!h;this.pb=f||!1;!this.pb&&(65<=lc("Chromium")||45<=lc("Firefox")||12<=lc("Safari")||Oc()&&Sc());a=ge();rh(this.s,a);this.v=new Kg(1E4);this.i=new ag(this.v.getValue());Ae(this,this.i);m=sh(this,m);Ue(this.i,"tick",m,!1,this);this.Z=new ag(6E5);Ae(this,this.Z);Ue(this.Z,"tick",m,!1,this);this.da||this.Z.start();
this.pb||(Ue(document,"visibilitychange",function(){"hidden"===document.visibilityState&&r.ka()}),Ue(document,"pagehide",this.ka,!1,this))}
v(ph,ef);function sh(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
ph.prototype.K=function(){this.ka();ef.prototype.K.call(this)};
function th(a){a.aa||(a.aa=.01>a.Sd()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.aa}
function uh(a,b){a.v=new Kg(1>b?1:b);a.i.setInterval(a.v.getValue())}
ph.prototype.log=function(a){a=a.clone();var b=this.Rd++;F(a,21,b);this.componentId&&F(a,26,this.componentId);if(!Od(a,1)){b=a;var c=Date.now().toString();F(b,1,c)}null==Od(a,15)&&F(a,15,60*(new Date).getTimezoneOffset());this.m&&(b=this.m.clone(),H(a,Jg,16,b));for(;this.j.length>=this.bufferSize;)this.j.shift(),++this.T;this.j.push(a);ff(this,new vh(a));this.da||this.i.enabled||this.i.start()};
ph.prototype.flush=function(a,b){var c=this;if(0===this.j.length)a&&a();else if(this.la)wh(this.s,3),Bh(this);else{var d=Date.now();if(this.Ub>d&&this.ya<d)b&&b("throttled");else{wh(this.s,1);var e=Ch(this.s,this.j,this.T,this.M);d={};var f=this.Sb();f&&(d.Authorization=f);var g=th(this);this.sessionIndex&&(d["X-Goog-AuthUser"]=this.sessionIndex,g=Fc(g,"authuser",this.sessionIndex));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=Fc(g,"pageId",this.pageId));if(f&&this.Tb===f)b&&b("stale-auth-token");
else{this.j=[];this.i.enabled&&this.i.stop();this.T=0;var h=e.serialize(),l;this.W&&this.W.isSupported(h.length)&&(l=this.W.compress(h));var m={url:g,body:h,Wd:1,Mc:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},p=function(u){c.v.reset();c.i.setInterval(c.v.getValue());if(u){var z=null;try{var D=JSON.parse(u.replace(")]}'\n",""));z=new mh(D)}catch(G){}z&&(u=Number(ie(Od(z,1),"-1")),0<u&&(c.ya=Date.now(),c.Ub=c.ya+u),z=oh.ctor?oh.i(z,oh.ctor,oh.h,!0):oh.isRepeated?
oh.i(z,oh.h,!0):oh.i(z,oh.h,oh.defaultValue,!0))&&(z=ie(Od(z,1),-1),-1!=z&&(c.Fb||uh(c,z)))}a&&a();c.M=0},r=function(u,z){var D=kh,G=E(e.V),M=!!(G&2);
D=be(e,D,3,M?1:2,G);if(!(M||E(D)&8)){for(M=0;M<D.length;M++){G=D[M];var P=ae(G);G!==P&&(D[M]=P)}xd(D,8)}M=c.v;M.h=Math.min(3E5,2*M.h);M.i=Math.min(3E5,M.h+Math.round(.2*(Math.random()-.5)*M.h));c.i.setInterval(c.v.getValue());401===u&&f&&(c.Tb=f);void 0===z&&(z=500<=u&&600>u||401===u||0===u);z&&(c.j=D.concat(c.j),c.da||c.i.enabled||c.i.start());b&&b("net-send-failed",u);++c.M},y=function(){c.network?c.network.send(m,p,r):c.Qd(m,p,r)};
l?l.then(function(u){m.Mc["Content-Encoding"]="gzip";m.Mc["Content-Type"]="application/binary";m.body=u;m.Wd=2;y()},function(){y()}):y()}}}};
ph.prototype.ka=function(){Dh(this.s,!0);this.flush();Dh(this.s,!1)};
function Bh(a){Eh(a,function(b,c){b=Fc(b,"format","json");var d=!1;try{d=window.navigator.sendBeacon(b,c.serialize())}catch(e){}a.la&&!d&&(a.la=!1);return d})}
function Eh(a,b){if(0!==a.j.length){var c=Jc(th(a),"format");c=Dc(c,"auth",a.Sb(),"authuser",a.sessionIndex||"0");for(var d=0;10>d&&a.j.length;++d){var e=a.j.slice(0,32),f=Ch(a.s,e,a.T,a.M);if(!b(c,f)){++a.M;break}a.T=0;a.M=0;a.j=a.j.slice(e.length)}a.i.enabled&&a.i.stop()}}
function vh(){Ce.call(this,"event-logged",void 0)}
v(vh,Ce);function qh(a,b){this.i=b=void 0===b?!1:b;this.uach=this.locale=null;this.h=new lh;F(this.h,2,a);b||(this.locale=document.documentElement.getAttribute("lang"));rh(this,new he)}
function rh(a,b){H(a.h,he,1,b);Od(b,1)||F(b,1,1);a.i||(b=Fh(a),Od(b,5)||F(b,5,a.locale));a.uach&&(b=Fh(a),$d(b,ih,9)||H(b,ih,9,a.uach))}
function wh(a,b){Ud($d(a.h,he,1))&&(a=Gh(a),F(a,1,b))}
function Dh(a,b){Ud($d(a.h,he,1))&&(a=Gh(a),F(a,2,b))}
function Hh(a,b){var c=void 0===c?jh:c;b(window,c).then(function(d){a.uach=d;d=Fh(a);H(d,ih,9,a.uach);return!0}).catch(function(){return!1})}
function Fh(a){a=$d(a.h,he,1);var b=$d(a,Wd,11);b||(b=new Wd,H(a,Wd,11,b));return b}
function Gh(a){a=Fh(a);var b=$d(a,hh,10);b||(b=new hh,F(b,2,!1),H(a,hh,10,b));return b}
function Ch(a,b,c,d){c=void 0===c?0:c;d=void 0===d?0:d;if(Ud($d(a.h,he,1))){var e=Gh(a);fe(e,3,d)}a=a.h.clone();d=Date.now().toString();a=F(a,4,d);b=de(a,kh,3,b);c&&F(b,14,c);return b}
;function Ih(a,b,c){Zg(a.url,function(d){d=d.target;if(gh(d)){try{var e=d.G?d.G.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Mc,a.timeoutMillis,a.withCredentials)}
;function Jh(a,b){J.call(this);this.s=a;this.Da=b;this.l="https://play.google.com/log?format=json&hasfast=true";this.m=!1;this.aa=Ih;this.i=""}
$a(Jh,J);function Kh(a,b,c,d,e,f){a=void 0===a?-1:a;b=void 0===b?"":b;c=void 0===c?"":c;d=void 0===d?!1:d;e=void 0===e?"":e;J.call(this);f?a=f:(a=new Jh(a,"0"),a.i=b,Ae(this,a),""!=c&&(a.l=c),d&&(a.m=!0),e&&(a.j=e),b=new ph(a.s,a.W?a.W:Ig,a.Da,a.aa,a.l,a.m,!1,a.ya,void 0,void 0,a.da?a.da:void 0),Ae(a,b),a.M&&rh(b.s,a.M),a.j&&(c=a.j,d=Fh(b.s),F(d,7,c)),a.Z&&(b.W=a.Z),a.i&&(b.componentId=a.i),a.v&&((c=a.v)?(b.m||(b.m=new Jg),c=c.serialize(),F(b.m,4,c)):b.m&&F(b.m,4)),a.ka&&(d=a.ka,b.m||(b.m=new Jg),c=b.m,null==
d?d=Hd:(e=E(d),1!==(e&1)&&(Object.isFrozen(d)&&(d=Array.prototype.slice.call(d)),zd(d,e|1))),F(c,2,d)),a.T&&(c=a.T,b.Fb=!0,uh(b,c)),a.la&&Hh(b.s,a.la),a=b);this.i=a}
v(Kh,J);
Kh.prototype.flush=function(a){var b=a||[];if(b.length){a=new vg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=e,g=new ug;var h=F(g,1,f.i);var l=f;g=[];for(var m=0;m<l.h.length;m++)g.push(l.h[m].Jb);if(null==g)g=F(h,3,Hd);else{l=E(g);if(!(l&4)){if(l&2||Object.isFrozen(g))g=Array.prototype.slice.call(g);for(m=0;m<g.length;m++)g[m]=g[m];zd(g,l|5)}g=F(h,3,g)}h=[];l=[];m=t(f.rb.keys());for(var p=m.next();!p.done;p=m.next())l.push(p.value.split(","));for(m=0;m<l.length;m++){p=l[m];var r=f.l;for(var y=f.xc(p)||
[],u=[],z=0;z<y.length;z++){var D=y[z];D=D&&D.bd;var G=new rg;switch(r){case 3:Yd(G,1,sg,Number(D));break;case 2:Yd(G,2,sg,Jd(Number(D)))}u.push(G)}r=u;for(y=0;y<r.length;y++){u=r[y];z=new tg;u=H(z,rg,2,u);z=p;D=[];G=f;for(var M=[],P=0;P<G.h.length;P++)M.push(G.h[P].Kb);G=M;for(M=0;M<G.length;M++){var T=G[M],da=z[M];P=new pg;switch(T){case 3:Yd(P,1,qg,String(da));break;case 2:T=P;da=Number(da);Qa(da);Yd(T,2,qg,da);break;case 1:Yd(P,3,qg,"true"==da)}D.push(P)}de(u,pg,1,D);h.push(u)}}de(g,tg,4,h);c.push(g);
e.clear()}de(a,ug,1,c);b=this.i;a instanceof kh?b.log(a):(c=new kh,a=a.serialize(),a=F(c,8,a),b.log(a));this.i.flush()}};function Lh(a){this.v=Mh();this.m=new Kh(1828);this.h=new cg(this.m);this.s=new ig(this.h);this.j=new jg(this.h);this.l=new kg(this.h);this.i=new gg(this.h);this.Ia=mg(a)}
function Mh(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function Nh(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function Oh(a){function b(z,D){Promise.resolve().then(function(){var G;null!=(G=c.na)&&G.s.record(Mh()-G.v,G.Ia);g.resolve({Ud:z,Te:D})})}
var c=this;this.i=!1;var d=a.program;var e=a.me;if(a.De){var f;this.na=null!=(f=a.na)?f:new Lh(e)}var g=new Nh;this.j=g.promise;if(x[e])if(x[e].a){var h;null!=(h=this.na)&&hg(h.i,h.Ia,3)}else{var l;null!=(l=this.na)&&hg(l.i,l.Ia,2);var m;null!=(m=this.na)&&m.h.ob()}else{var p;null!=(p=this.na)&&hg(p.i,p.Ia,1);var r;null!=(r=this.na)&&r.h.ob()}try{this.l=t((0,x[e].a)(d,b,!0)).next().value,this.Se=g.promise.then(function(){})}catch(z){var y;
null!=(y=this.na)&&hg(y.i,y.Ia,4);var u;null!=(u=this.na)&&u.h.ob();throw z;}}
Oh.prototype.snapshot=function(a){var b=this;if(this.i)throw Error("Already disposed");var c=Mh(),d;null!=(d=this.na)&&d.j.h.pc("/client_streamz/bg/fsc",d.Ia);return this.j.then(function(e){var f=e.Ud;return new Promise(function(g){f(function(h){var l;null!=(l=b.na)&&l.l.record(Mh()-c,l.Ia);g(h)},[a.cd,
a.Ue])})})};
Oh.prototype.Ed=function(a){if(this.i)throw Error("Already disposed");var b=Mh(),c;null!=(c=this.na)&&c.j.h.pc("/client_streamz/bg/fsc",c.Ia);a=this.l([a.cd,a.Ue]);var d;null!=(d=this.na)&&d.l.record(Mh()-b,d.Ia);return a};
Oh.prototype.dispose=function(){var a;null!=(a=this.na)&&a.h.ob();this.i=!0;this.j.then(function(b){(b=b.Te)&&b()})};
Oh.prototype.h=function(){return this.i};var Ph=window;Ab("csi.gstatic.com");Ab("googleads.g.doubleclick.net");Ab("partner.googleadservices.com");Ab("pubads.g.doubleclick.net");Ab("securepubads.g.doubleclick.net");Ab("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var Qh;try{new URL("s://g"),Qh=!0}catch(a){Qh=!1}var Rh=Qh;function Sh(a){if(a instanceof Kb)a=Lb(a);else{b:if(Rh){try{var b=new URL(a)}catch(c){b="https:";break b}b=b.protocol}else c:{b=document.createElement("a");try{b.href=a}catch(c){b=void 0;break c}b=b.protocol;b=":"===b||""===b?"https:":b}a="javascript:"!==b?a:void 0}return a}
;var Th={};function Uh(){}
function Vh(a){this.h=a}
v(Vh,Uh);Vh.prototype.toString=function(){return this.h};function Wh(a){var b="true".toString(),c=[new Vh(Xh[0].toLowerCase(),Th)];if(0===c.length)throw Error("");if(c.map(function(d){if(d instanceof Vh)d=d.h;else throw Error("");return d}).every(function(d){return 0!=="data-loaded".indexOf(d)}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;function Yh(){throw Error("unknown trace type");}
;function Zh(a){var b,c,d=null==(c=(b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:c.call(b,"script[nonce]");(b=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",b)}
function $h(a,b){a.src=Eb(b);Zh(a)}
;(function(){return""}).toString().indexOf("`");function ai(a){this.se=a}
function bi(a){return new ai(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var ci=[bi("data"),bi("http"),bi("https"),bi("mailto"),bi("ftp"),new ai(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function di(a){var b=ei;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function fi(){var a=[];di(function(b){a.push(b)});
return a}
var ei={bf:"allow-forms",cf:"allow-modals",df:"allow-orientation-lock",ef:"allow-pointer-lock",ff:"allow-popups",gf:"allow-popups-to-escape-sandbox",hf:"allow-presentation",jf:"allow-same-origin",kf:"allow-scripts",lf:"allow-top-navigation",mf:"allow-top-navigation-by-user-activation"},gi=eb(function(){return fi()});
function hi(){var a=ii(),b={};gb(gi(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function ii(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function ji(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var ki=(new Date).getTime();var li="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");[].concat(ia(li),["client_dev_set_cookie"]);"undefined"!==typeof TextDecoder&&new TextDecoder;var mi="undefined"!==typeof TextEncoder?new TextEncoder:null,ni=mi?function(a){return mi.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
128>e?b[c++]=e:(2048>e?b[c++]=e>>6|192:(55296==(e&64512)&&d+1<a.length&&56320==(a.charCodeAt(d+1)&64512)?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};function oi(a){ef.call(this);var b=this;this.v=this.j=0;this.Aa=null!=a?a:{ma:function(e,f){return setTimeout(e,f)},
Fa:function(e){clearTimeout(e)}};
var c,d;this.i=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.m=function(){return w(function(e){return e.yield(pi(b),0)})};
window.addEventListener("offline",this.m);window.addEventListener("online",this.m);this.v||qi(this)}
v(oi,ef);function ri(){var a=si;oi.h||(oi.h=new oi(a));return oi.h}
oi.prototype.dispose=function(){window.removeEventListener("offline",this.m);window.removeEventListener("online",this.m);this.Aa.Fa(this.v);delete oi.h};
oi.prototype.sa=function(){return this.i};
function qi(a){a.v=a.Aa.ma(function(){var b;return w(function(c){if(1==c.h)return a.i?(null==(b=window.navigator)?0:b.onLine)?c.A(3):c.yield(pi(a),3):c.yield(pi(a),3);qi(a);c.h=0})},3E4)}
function pi(a,b){return a.s?a.s:a.s=new Promise(function(c){var d,e,f,g;return w(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,Aa(h,2,3),d&&(a.j=a.Aa.ma(function(){d.abort()},b||2E4)),h.yield(fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:Da(h);a.s=void 0;a.j&&(a.Aa.Fa(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?ff(a,"networkstatus-online"):ff(a,"networkstatus-offline"));c(g);Ea(h);break;case 2:Ca(h),g=!1,h.A(3)}})})}
;function ti(){this.data_=[];this.h=-1}
ti.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data_[a]!==b&&(this.data_[a]=b,this.h=-1)};
ti.prototype.get=function(a){return!!this.data_[a]};
function ui(a){-1===a.h&&(a.h=ib(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function vi(a,b){this.h=a[x.Symbol.iterator]();this.i=b}
vi.prototype[Symbol.iterator]=function(){return this};
vi.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value),done:a.done}};
function wi(a,b){return new vi(a,b)}
;function xi(){this.blockSize=-1}
;function yi(){this.blockSize=-1;this.blockSize=64;this.h=[];this.m=[];this.s=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
$a(yi,xi);yi.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function zi(a,b,c){c||(c=0);var d=a.s;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],l=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var m=1518500249}else f=c^g^h,m=1859775393;else 60>e?(f=c&g|h&(c|g),m=2400959708):
(f=c^g^h,m=3395469782);f=(b<<5|b>>>27)+f+l+m+d[e]&4294967295;l=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+l&4294967295}
yi.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.m,f=this.i;d<b;){if(0==f)for(;d<=c;)zi(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){zi(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){zi(this,e);f=0;break}}this.i=f;this.l+=b}};
yi.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.m[c]=b&255,b/=256;zi(this,this.m);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function Ai(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Bi(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Ci(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Ai(a).match(/\S+/g)||[],b=0<=fb(a,b));return b}
function Di(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Ci(a,"inverted-hdpi")&&Bi(a,Array.prototype.filter.call(a.classList?a.classList:Ai(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function Ei(){}
Ei.prototype.next=function(){return Fi};
var Fi={done:!0,value:void 0};function Gi(a){return{value:a,done:!1}}
Ei.prototype.Ea=function(){return this};function Hi(a){if(a instanceof Ii||a instanceof Ji||a instanceof Ki)return a;if("function"==typeof a.next)return new Ii(function(){return a});
if("function"==typeof a[Symbol.iterator])return new Ii(function(){return a[Symbol.iterator]()});
if("function"==typeof a.Ea)return new Ii(function(){return a.Ea()});
throw Error("Not an iterator or iterable.");}
function Ii(a){this.i=a}
Ii.prototype.Ea=function(){return new Ji(this.i())};
Ii.prototype[Symbol.iterator]=function(){return new Ki(this.i())};
Ii.prototype.h=function(){return new Ki(this.i())};
function Ji(a){this.i=a}
v(Ji,Ei);Ji.prototype.next=function(){return this.i.next()};
Ji.prototype[Symbol.iterator]=function(){return new Ki(this.i)};
Ji.prototype.h=function(){return new Ki(this.i)};
function Ki(a){Ii.call(this,function(){return a});
this.j=a}
v(Ki,Ii);Ki.prototype.next=function(){return this.j.next()};function Li(a,b){this.i={};this.h=[];this.j=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof Li)for(c=a.Ac(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
k=Li.prototype;k.Ac=function(){Mi(this);return this.h.concat()};
k.has=function(a){return Ni(this.i,a)};
k.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||Oi;Mi(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function Oi(a,b){return a===b}
k.isEmpty=function(){return 0==this.size};
k.clear=function(){this.i={};this.j=this.size=this.h.length=0};
k.remove=function(a){return this.delete(a)};
k.delete=function(a){return Ni(this.i,a)?(delete this.i[a],--this.size,this.j++,this.h.length>2*this.size&&Mi(this),!0):!1};
function Mi(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];Ni(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],Ni(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
k.get=function(a,b){return Ni(this.i,a)?this.i[a]:b};
k.set=function(a,b){Ni(this.i,a)||(this.size+=1,this.h.push(a),this.j++);this.i[a]=b};
k.forEach=function(a,b){for(var c=this.Ac(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
k.clone=function(){return new Li(this)};
k.keys=function(){return Hi(this.Ea(!0)).h()};
k.values=function(){return Hi(this.Ea(!1)).h()};
k.entries=function(){var a=this;return wi(this.keys(),function(b){return[b,a.get(b)]})};
k.Ea=function(a){Mi(this);var b=0,c=this.j,d=this,e=new Ei;e.next=function(){if(c!=d.j)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return Fi;var f=d.h[b++];return Gi(a?f:d.i[f])};
return e};
function Ni(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function Pi(a){J.call(this);this.s=1;this.l=[];this.m=0;this.i=[];this.j={};this.v=!!a}
$a(Pi,J);k=Pi.prototype;k.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.s;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.s=e+3;d.push(e);return e};
function Qi(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.Eb(b)}}
k.Eb=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=function(){}):(c&&kb(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
k.bb=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.v)for(e=0;e<c.length;e++){var g=c[e];Ri(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.h();e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.Eb(c)}}return 0!=e}return!1};
function Ri(a,b,c){Df(function(){a.apply(b,c)})}
k.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.Eb,this),delete this.j[a])}else this.i.length=0,this.j={}};
k.K=function(){Pi.xa.K.call(this);this.clear();this.l.length=0};function Si(a){this.h=a}
Si.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,(new Lg).serialize(b))};
Si.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Si.prototype.remove=function(a){this.h.remove(a)};function Ti(a){this.h=a}
$a(Ti,Si);function Ui(a){this.data=a}
function Vi(a){return void 0===a||a instanceof Ui?a:new Ui(a)}
Ti.prototype.set=function(a,b){Ti.xa.set.call(this,a,Vi(b))};
Ti.prototype.i=function(a){a=Ti.xa.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Ti.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Wi(a){this.h=a}
$a(Wi,Ti);Wi.prototype.set=function(a,b,c){if(b=Vi(b)){if(c){if(c<Date.now()){Wi.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}Wi.xa.set.call(this,a,b)};
Wi.prototype.i=function(a){var b=Wi.xa.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())Wi.prototype.remove.call(this,a);else return b}};function Xi(){}
;function Yi(){}
$a(Yi,Xi);Yi.prototype[Symbol.iterator]=function(){return Hi(this.Ea(!0)).h()};
Yi.prototype.clear=function(){var a=Array.from(this);a=t(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function Zi(a){this.h=a}
$a(Zi,Yi);k=Zi.prototype;k.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
k.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
k.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
k.remove=function(a){this.h.removeItem(a)};
k.Ea=function(a){var b=0,c=this.h,d=new Ei;d.next=function(){if(b>=c.length)return Fi;var e=c.key(b++);if(a)return Gi(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Gi(e)};
return d};
k.clear=function(){this.h.clear()};
k.key=function(a){return this.h.key(a)};function $i(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
$a($i,Zi);function aj(a,b){this.i=a;this.h=null;var c;if(c=$c)c=!(9<=Number(nd));if(c){bj||(bj=new Li);this.h=bj.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),bj.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
$a(aj,Yi);var cj={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},bj=null;function dj(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return cj[b]})}
k=aj.prototype;k.isAvailable=function(){return!!this.h};
k.set=function(a,b){this.h.setAttribute(dj(a),b);ej(this)};
k.get=function(a){a=this.h.getAttribute(dj(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
k.remove=function(a){this.h.removeAttribute(dj(a));ej(this)};
k.Ea=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new Ei;d.next=function(){if(b>=c.length)return Fi;var e=c[b++];if(a)return Gi(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Gi(e)};
return d};
k.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);ej(this)};
function ej(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function fj(a,b){this.i=a;this.h=b+"::"}
$a(fj,Yi);fj.prototype.set=function(a,b){this.i.set(this.h+a,b)};
fj.prototype.get=function(a){return this.i.get(this.h+a)};
fj.prototype.remove=function(a){this.i.remove(this.h+a)};
fj.prototype.Ea=function(a){var b=this.i[Symbol.iterator](),c=this,d=new Ei;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return Gi(a?e.slice(c.h.length):c.i.get(e))};
return d};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var K={},gj="undefined"!==typeof Uint8Array&&"undefined"!==typeof Uint16Array&&"undefined"!==typeof Int32Array;K.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if("object"!==typeof c)throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
K.Pc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var hj={qb:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
ed:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},ij={qb:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
ed:function(a){return[].concat.apply([],a)}};
K.Re=function(){gj?(K.nb=Uint8Array,K.Ja=Uint16Array,K.Nd=Int32Array,K.assign(K,hj)):(K.nb=Array,K.Ja=Array,K.Nd=Array,K.assign(K,ij))};
K.Re();var jj=!0;try{new Uint8Array(1)}catch(a){jj=!1}
function kj(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if(55296===(f&64512)&&b+1<d){var g=a.charCodeAt(b+1);56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=128>f?1:2048>f?2:65536>f?3:4}var h=new K.nb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),55296===(f&64512)&&b+1<d&&(g=a.charCodeAt(b+1),56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)),128>f?h[c++]=f:(2048>f?h[c++]=192|f>>>6:(65536>f?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var lj={};lj=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;0!==c;){f=2E3<c?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var mj={},nj,oj=[],pj=0;256>pj;pj++){nj=pj;for(var qj=0;8>qj;qj++)nj=nj&1?3988292384^nj>>>1:nj>>>1;oj[pj]=nj}mj=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^oj[(a^b[d])&255];return a^-1};var rj={};rj={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function sj(a){for(var b=a.length;0<=--b;)a[b]=0}
var tj=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],uj=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],vj=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],wj=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],xj=Array(576);sj(xj);var yj=Array(60);sj(yj);var zj=Array(512);sj(zj);var Aj=Array(256);sj(Aj);var Bj=Array(29);sj(Bj);var Cj=Array(30);sj(Cj);function Dj(a,b,c,d,e){this.Fd=a;this.ge=b;this.ee=c;this.ae=d;this.xe=e;this.kd=a&&a.length}
var Ej,Fj,Gj;function Hj(a,b){this.dd=a;this.xb=0;this.Wa=b}
function Ij(a,b){a.S[a.pending++]=b&255;a.S[a.pending++]=b>>>8&255}
function Jj(a,b,c){a.ba>16-c?(a.ja|=b<<a.ba&65535,Ij(a,a.ja),a.ja=b>>16-a.ba,a.ba+=c-16):(a.ja|=b<<a.ba&65535,a.ba+=c)}
function Kj(a,b,c){Jj(a,c[2*b],c[2*b+1])}
function Lj(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(0<--b);return c>>>1}
function Mj(a,b,c){var d=Array(16),e=0,f;for(f=1;15>=f;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[2*c+1],0!==e&&(a[2*c]=Lj(d[e]++,e))}
function Nj(a){var b;for(b=0;286>b;b++)a.oa[2*b]=0;for(b=0;30>b;b++)a.cb[2*b]=0;for(b=0;19>b;b++)a.ea[2*b]=0;a.oa[512]=1;a.Qa=a.Ab=0;a.va=a.matches=0}
function Oj(a){8<a.ba?Ij(a,a.ja):0<a.ba&&(a.S[a.pending++]=a.ja);a.ja=0;a.ba=0}
function Pj(a,b,c){Oj(a);Ij(a,c);Ij(a,~c);K.qb(a.S,a.window,b,c,a.pending);a.pending+=c}
function Qj(a,b,c,d){var e=2*b,f=2*c;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function Rj(a,b,c){for(var d=a.U[c],e=c<<1;e<=a.Na;){e<a.Na&&Qj(b,a.U[e+1],a.U[e],a.depth)&&e++;if(Qj(b,d,a.U[e],a.depth))break;a.U[c]=a.U[e];c=e;e<<=1}a.U[c]=d}
function Sj(a,b,c){var d=0;if(0!==a.va){do{var e=a.S[a.Hb+2*d]<<8|a.S[a.Hb+2*d+1];var f=a.S[a.Fc+d];d++;if(0===e)Kj(a,f,b);else{var g=Aj[f];Kj(a,g+256+1,b);var h=tj[g];0!==h&&(f-=Bj[g],Jj(a,f,h));e--;g=256>e?zj[e]:zj[256+(e>>>7)];Kj(a,g,c);h=uj[g];0!==h&&(e-=Cj[g],Jj(a,e,h))}}while(d<a.va)}Kj(a,256,b)}
function Tj(a,b){var c=b.dd,d=b.Wa.Fd,e=b.Wa.kd,f=b.Wa.ae,g,h=-1;a.Na=0;a.ub=573;for(g=0;g<f;g++)0!==c[2*g]?(a.U[++a.Na]=h=g,a.depth[g]=0):c[2*g+1]=0;for(;2>a.Na;){var l=a.U[++a.Na]=2>h?++h:0;c[2*l]=1;a.depth[l]=0;a.Qa--;e&&(a.Ab-=d[2*l+1])}b.xb=h;for(g=a.Na>>1;1<=g;g--)Rj(a,c,g);l=f;do g=a.U[1],a.U[1]=a.U[a.Na--],Rj(a,c,1),d=a.U[1],a.U[--a.ub]=g,a.U[--a.ub]=d,c[2*l]=c[2*g]+c[2*d],a.depth[l]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[2*g+1]=c[2*d+1]=l,a.U[1]=l++,Rj(a,c,1);while(2<=a.Na);a.U[--a.ub]=
a.U[1];g=b.dd;l=b.xb;d=b.Wa.Fd;e=b.Wa.kd;f=b.Wa.ge;var m=b.Wa.ee,p=b.Wa.xe,r,y=0;for(r=0;15>=r;r++)a.Ka[r]=0;g[2*a.U[a.ub]+1]=0;for(b=a.ub+1;573>b;b++){var u=a.U[b];r=g[2*g[2*u+1]+1]+1;r>p&&(r=p,y++);g[2*u+1]=r;if(!(u>l)){a.Ka[r]++;var z=0;u>=m&&(z=f[u-m]);var D=g[2*u];a.Qa+=D*(r+z);e&&(a.Ab+=D*(d[2*u+1]+z))}}if(0!==y){do{for(r=p-1;0===a.Ka[r];)r--;a.Ka[r]--;a.Ka[r+1]+=2;a.Ka[p]--;y-=2}while(0<y);for(r=p;0!==r;r--)for(u=a.Ka[r];0!==u;)d=a.U[--b],d>l||(g[2*d+1]!==r&&(a.Qa+=(r-g[2*d+1])*g[2*d],g[2*
d+1]=r),u--)}Mj(c,h,a.Ka)}
function Uj(a,b,c){var d,e=-1,f=b[1],g=0,h=7,l=4;0===f&&(h=138,l=3);b[2*(c+1)+1]=65535;for(d=0;d<=c;d++){var m=f;f=b[2*(d+1)+1];++g<h&&m===f||(g<l?a.ea[2*m]+=g:0!==m?(m!==e&&a.ea[2*m]++,a.ea[32]++):10>=g?a.ea[34]++:a.ea[36]++,g=0,e=m,0===f?(h=138,l=3):m===f?(h=6,l=3):(h=7,l=4))}}
function Vj(a,b,c){var d,e=-1,f=b[1],g=0,h=7,l=4;0===f&&(h=138,l=3);for(d=0;d<=c;d++){var m=f;f=b[2*(d+1)+1];if(!(++g<h&&m===f)){if(g<l){do Kj(a,m,a.ea);while(0!==--g)}else 0!==m?(m!==e&&(Kj(a,m,a.ea),g--),Kj(a,16,a.ea),Jj(a,g-3,2)):10>=g?(Kj(a,17,a.ea),Jj(a,g-3,3)):(Kj(a,18,a.ea),Jj(a,g-11,7));g=0;e=m;0===f?(h=138,l=3):m===f?(h=6,l=3):(h=7,l=4)}}}
function Wj(a){var b=4093624447,c;for(c=0;31>=c;c++,b>>>=1)if(b&1&&0!==a.oa[2*c])return 0;if(0!==a.oa[18]||0!==a.oa[20]||0!==a.oa[26])return 1;for(c=32;256>c;c++)if(0!==a.oa[2*c])return 1;return 0}
var Xj=!1;function Yj(a,b,c){a.S[a.Hb+2*a.va]=b>>>8&255;a.S[a.Hb+2*a.va+1]=b&255;a.S[a.Fc+a.va]=c&255;a.va++;0===b?a.oa[2*c]++:(a.matches++,b--,a.oa[2*(Aj[c]+256+1)]++,a.cb[2*(256>b?zj[b]:zj[256+(b>>>7)])]++);return a.va===a.Lb-1}
;function Zj(a,b){a.msg=rj[b];return b}
function ak(a){for(var b=a.length;0<=--b;)a[b]=0}
function bk(a){var b=a.state,c=b.pending;c>a.I&&(c=a.I);0!==c&&(K.qb(a.output,b.S,b.Mb,c,a.yb),a.yb+=c,b.Mb+=c,a.Qc+=c,a.I-=c,b.pending-=c,0===b.pending&&(b.Mb=0))}
function ck(a,b){var c=0<=a.ra?a.ra:-1,d=a.o-a.ra,e=0;if(0<a.level){2===a.F.vc&&(a.F.vc=Wj(a));Tj(a,a.fc);Tj(a,a.ac);Uj(a,a.oa,a.fc.xb);Uj(a,a.cb,a.ac.xb);Tj(a,a.Xc);for(e=18;3<=e&&0===a.ea[2*wj[e]+1];e--);a.Qa+=3*(e+1)+14;var f=a.Qa+3+7>>>3;var g=a.Ab+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&-1!==c)Jj(a,b?1:0,3),Pj(a,c,d);else if(4===a.strategy||g===f)Jj(a,2+(b?1:0),3),Sj(a,xj,yj);else{Jj(a,4+(b?1:0),3);c=a.fc.xb+1;d=a.ac.xb+1;e+=1;Jj(a,c-257,5);Jj(a,d-1,5);Jj(a,e-4,4);for(f=0;f<e;f++)Jj(a,a.ea[2*
wj[f]+1],3);Vj(a,a.oa,c-1);Vj(a,a.cb,d-1);Sj(a,a.oa,a.cb)}Nj(a);b&&Oj(a);a.ra=a.o;bk(a.F)}
function N(a,b){a.S[a.pending++]=b}
function dk(a,b){a.S[a.pending++]=b>>>8&255;a.S[a.pending++]=b&255}
function ek(a,b){var c=a.qd,d=a.o,e=a.ta,f=a.sd,g=a.o>a.ha-262?a.o-(a.ha-262):0,h=a.window,l=a.Xa,m=a.Ha,p=a.o+258,r=h[d+e-1],y=h[d+e];a.ta>=a.jd&&(c>>=2);f>a.u&&(f=a.u);do{var u=b;if(h[u+e]===y&&h[u+e-1]===r&&h[u]===h[d]&&h[++u]===h[d+1]){d+=2;for(u++;h[++d]===h[++u]&&h[++d]===h[++u]&&h[++d]===h[++u]&&h[++d]===h[++u]&&h[++d]===h[++u]&&h[++d]===h[++u]&&h[++d]===h[++u]&&h[++d]===h[++u]&&d<p;);u=258-(p-d);d=p-258;if(u>e){a.wb=b;e=u;if(u>=f)break;r=h[d+e-1];y=h[d+e]}}}while((b=m[b&l])>g&&0!==--c);return e<=
a.u?e:a.u}
function fk(a){var b=a.ha,c;do{var d=a.Ld-a.u-a.o;if(a.o>=b+(b-262)){K.qb(a.window,a.window,b,b,0);a.wb-=b;a.o-=b;a.ra-=b;var e=c=a.ec;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Ha[--e],a.Ha[e]=f>=b?f-b:0;while(--c);d+=b}if(0===a.F.ia)break;e=a.F;c=a.window;f=a.o+a.u;var g=e.ia;g>d&&(g=d);0===g?c=0:(e.ia-=g,K.qb(c,e.input,e.gb,g,f),1===e.state.wrap?e.D=lj(e.D,c,g,f):2===e.state.wrap&&(e.D=mj(e.D,c,g,f)),e.gb+=g,e.kb+=g,c=g);a.u+=c;if(3<=a.u+a.qa)for(d=a.o-a.qa,a.H=a.window[d],
a.H=(a.H<<a.Ma^a.window[d+1])&a.La;a.qa&&!(a.H=(a.H<<a.Ma^a.window[d+3-1])&a.La,a.Ha[d&a.Xa]=a.head[a.H],a.head[a.H]=d,d++,a.qa--,3>a.u+a.qa););}while(262>a.u&&0!==a.F.ia)}
function gk(a,b){for(var c;;){if(262>a.u){fk(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.H=(a.H<<a.Ma^a.window[a.o+3-1])&a.La,c=a.Ha[a.o&a.Xa]=a.head[a.H],a.head[a.H]=a.o);0!==c&&a.o-c<=a.ha-262&&(a.J=ek(a,c));if(3<=a.J)if(c=Yj(a,a.o-a.wb,a.J-3),a.u-=a.J,a.J<=a.Gc&&3<=a.u){a.J--;do a.o++,a.H=(a.H<<a.Ma^a.window[a.o+3-1])&a.La,a.Ha[a.o&a.Xa]=a.head[a.H],a.head[a.H]=a.o;while(0!==--a.J);a.o++}else a.o+=a.J,a.J=0,a.H=a.window[a.o],a.H=(a.H<<a.Ma^a.window[a.o+1])&a.La;else c=Yj(a,0,
a.window[a.o]),a.u--,a.o++;if(c&&(ck(a,!1),0===a.F.I))return 1}a.qa=2>a.o?a.o:2;return 4===b?(ck(a,!0),0===a.F.I?3:4):a.va&&(ck(a,!1),0===a.F.I)?1:2}
function hk(a,b){for(var c,d;;){if(262>a.u){fk(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.H=(a.H<<a.Ma^a.window[a.o+3-1])&a.La,c=a.Ha[a.o&a.Xa]=a.head[a.H],a.head[a.H]=a.o);a.ta=a.J;a.vd=a.wb;a.J=2;0!==c&&a.ta<a.Gc&&a.o-c<=a.ha-262&&(a.J=ek(a,c),5>=a.J&&(1===a.strategy||3===a.J&&4096<a.o-a.wb)&&(a.J=2));if(3<=a.ta&&a.J<=a.ta){d=a.o+a.u-3;c=Yj(a,a.o-1-a.vd,a.ta-3);a.u-=a.ta-1;a.ta-=2;do++a.o<=d&&(a.H=(a.H<<a.Ma^a.window[a.o+3-1])&a.La,a.Ha[a.o&a.Xa]=a.head[a.H],a.head[a.H]=a.o);
while(0!==--a.ta);a.eb=0;a.J=2;a.o++;if(c&&(ck(a,!1),0===a.F.I))return 1}else if(a.eb){if((c=Yj(a,0,a.window[a.o-1]))&&ck(a,!1),a.o++,a.u--,0===a.F.I)return 1}else a.eb=1,a.o++,a.u--}a.eb&&(Yj(a,0,a.window[a.o-1]),a.eb=0);a.qa=2>a.o?a.o:2;return 4===b?(ck(a,!0),0===a.F.I?3:4):a.va&&(ck(a,!1),0===a.F.I)?1:2}
function ik(a,b){for(var c,d,e,f=a.window;;){if(258>=a.u){fk(a);if(258>=a.u&&0===b)return 1;if(0===a.u)break}a.J=0;if(3<=a.u&&0<a.o&&(d=a.o-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.o+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.J=258-(e-d);a.J>a.u&&(a.J=a.u)}3<=a.J?(c=Yj(a,1,a.J-3),a.u-=a.J,a.o+=a.J,a.J=0):(c=Yj(a,0,a.window[a.o]),a.u--,a.o++);if(c&&(ck(a,!1),0===a.F.I))return 1}a.qa=0;return 4===b?(ck(a,!0),0===a.F.I?3:4):
a.va&&(ck(a,!1),0===a.F.I)?1:2}
function jk(a,b){for(var c;;){if(0===a.u&&(fk(a),0===a.u)){if(0===b)return 1;break}a.J=0;c=Yj(a,0,a.window[a.o]);a.u--;a.o++;if(c&&(ck(a,!1),0===a.F.I))return 1}a.qa=0;return 4===b?(ck(a,!0),0===a.F.I?3:4):a.va&&(ck(a,!1),0===a.F.I)?1:2}
function kk(a,b,c,d,e){this.ne=a;this.we=b;this.ze=c;this.ue=d;this.je=e}
var lk;lk=[new kk(0,0,0,0,function(a,b){var c=65535;for(c>a.wa-5&&(c=a.wa-5);;){if(1>=a.u){fk(a);if(0===a.u&&0===b)return 1;if(0===a.u)break}a.o+=a.u;a.u=0;var d=a.ra+c;if(0===a.o||a.o>=d)if(a.u=a.o-d,a.o=d,ck(a,!1),0===a.F.I)return 1;if(a.o-a.ra>=a.ha-262&&(ck(a,!1),0===a.F.I))return 1}a.qa=0;if(4===b)return ck(a,!0),0===a.F.I?3:4;a.o>a.ra&&ck(a,!1);return 1}),
new kk(4,4,8,4,gk),new kk(4,5,16,8,gk),new kk(4,6,32,32,gk),new kk(4,4,16,16,hk),new kk(8,16,32,32,hk),new kk(8,16,128,128,hk),new kk(8,32,128,256,hk),new kk(32,128,258,1024,hk),new kk(32,258,258,4096,hk)];
function mk(){this.F=null;this.status=0;this.S=null;this.wrap=this.pending=this.Mb=this.wa=0;this.B=null;this.za=0;this.method=8;this.vb=-1;this.Xa=this.Sc=this.ha=0;this.window=null;this.Ld=0;this.head=this.Ha=null;this.sd=this.jd=this.strategy=this.level=this.Gc=this.qd=this.ta=this.u=this.wb=this.o=this.eb=this.vd=this.J=this.ra=this.Ma=this.La=this.Bc=this.ec=this.H=0;this.oa=new K.Ja(1146);this.cb=new K.Ja(122);this.ea=new K.Ja(78);ak(this.oa);ak(this.cb);ak(this.ea);this.Xc=this.ac=this.fc=
null;this.Ka=new K.Ja(16);this.U=new K.Ja(573);ak(this.U);this.ub=this.Na=0;this.depth=new K.Ja(573);ak(this.depth);this.ba=this.ja=this.qa=this.matches=this.Ab=this.Qa=this.Hb=this.va=this.Lb=this.Fc=0}
function nk(a,b){if(!a||!a.state||5<b||0>b)return a?Zj(a,-2):-2;var c=a.state;if(!a.output||!a.input&&0!==a.ia||666===c.status&&4!==b)return Zj(a,0===a.I?-5:-2);c.F=a;var d=c.vb;c.vb=b;if(42===c.status)if(2===c.wrap)a.D=0,N(c,31),N(c,139),N(c,8),c.B?(N(c,(c.B.text?1:0)+(c.B.Ua?2:0)+(c.B.Ta?4:0)+(c.B.name?8:0)+(c.B.comment?16:0)),N(c,c.B.time&255),N(c,c.B.time>>8&255),N(c,c.B.time>>16&255),N(c,c.B.time>>24&255),N(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),N(c,c.B.os&255),c.B.Ta&&c.B.Ta.length&&
(N(c,c.B.Ta.length&255),N(c,c.B.Ta.length>>8&255)),c.B.Ua&&(a.D=mj(a.D,c.S,c.pending,0)),c.za=0,c.status=69):(N(c,0),N(c,0),N(c,0),N(c,0),N(c,0),N(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),N(c,3),c.status=113);else{var e=8+(c.Sc-8<<4)<<8;e|=(2<=c.strategy||2>c.level?0:6>c.level?1:6===c.level?2:3)<<6;0!==c.o&&(e|=32);c.status=113;dk(c,e+(31-e%31));0!==c.o&&(dk(c,a.D>>>16),dk(c,a.D&65535));a.D=1}if(69===c.status)if(c.B.Ta){for(e=c.pending;c.za<(c.B.Ta.length&65535)&&(c.pending!==c.wa||(c.B.Ua&&
c.pending>e&&(a.D=mj(a.D,c.S,c.pending-e,e)),bk(a),e=c.pending,c.pending!==c.wa));)N(c,c.B.Ta[c.za]&255),c.za++;c.B.Ua&&c.pending>e&&(a.D=mj(a.D,c.S,c.pending-e,e));c.za===c.B.Ta.length&&(c.za=0,c.status=73)}else c.status=73;if(73===c.status)if(c.B.name){e=c.pending;do{if(c.pending===c.wa&&(c.B.Ua&&c.pending>e&&(a.D=mj(a.D,c.S,c.pending-e,e)),bk(a),e=c.pending,c.pending===c.wa)){var f=1;break}f=c.za<c.B.name.length?c.B.name.charCodeAt(c.za++)&255:0;N(c,f)}while(0!==f);c.B.Ua&&c.pending>e&&(a.D=mj(a.D,
c.S,c.pending-e,e));0===f&&(c.za=0,c.status=91)}else c.status=91;if(91===c.status)if(c.B.comment){e=c.pending;do{if(c.pending===c.wa&&(c.B.Ua&&c.pending>e&&(a.D=mj(a.D,c.S,c.pending-e,e)),bk(a),e=c.pending,c.pending===c.wa)){f=1;break}f=c.za<c.B.comment.length?c.B.comment.charCodeAt(c.za++)&255:0;N(c,f)}while(0!==f);c.B.Ua&&c.pending>e&&(a.D=mj(a.D,c.S,c.pending-e,e));0===f&&(c.status=103)}else c.status=103;103===c.status&&(c.B.Ua?(c.pending+2>c.wa&&bk(a),c.pending+2<=c.wa&&(N(c,a.D&255),N(c,a.D>>
8&255),a.D=0,c.status=113)):c.status=113);if(0!==c.pending){if(bk(a),0===a.I)return c.vb=-1,0}else if(0===a.ia&&(b<<1)-(4<b?9:0)<=(d<<1)-(4<d?9:0)&&4!==b)return Zj(a,-5);if(666===c.status&&0!==a.ia)return Zj(a,-5);if(0!==a.ia||0!==c.u||0!==b&&666!==c.status){d=2===c.strategy?jk(c,b):3===c.strategy?ik(c,b):lk[c.level].je(c,b);if(3===d||4===d)c.status=666;if(1===d||3===d)return 0===a.I&&(c.vb=-1),0;if(2===d&&(1===b?(Jj(c,2,3),Kj(c,256,xj),16===c.ba?(Ij(c,c.ja),c.ja=0,c.ba=0):8<=c.ba&&(c.S[c.pending++]=
c.ja&255,c.ja>>=8,c.ba-=8)):5!==b&&(Jj(c,0,3),Pj(c,0,0),3===b&&(ak(c.head),0===c.u&&(c.o=0,c.ra=0,c.qa=0))),bk(a),0===a.I))return c.vb=-1,0}if(4!==b)return 0;if(0>=c.wrap)return 1;2===c.wrap?(N(c,a.D&255),N(c,a.D>>8&255),N(c,a.D>>16&255),N(c,a.D>>24&255),N(c,a.kb&255),N(c,a.kb>>8&255),N(c,a.kb>>16&255),N(c,a.kb>>24&255)):(dk(c,a.D>>>16),dk(c,a.D&65535));bk(a);0<c.wrap&&(c.wrap=-c.wrap);return 0!==c.pending?0:1}
;var ok={};ok=function(){this.input=null;this.kb=this.ia=this.gb=0;this.output=null;this.Qc=this.I=this.yb=0;this.msg="";this.state=null;this.vc=2;this.D=0};var pk=Object.prototype.toString;
function qk(a){if(!(this instanceof qk))return new qk(a);a=this.options=K.assign({level:-1,method:8,chunkSize:16384,windowBits:15,memLevel:8,strategy:0,to:""},a||{});a.raw&&0<a.windowBits?a.windowBits=-a.windowBits:a.gzip&&0<a.windowBits&&16>a.windowBits&&(a.windowBits+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.F=new ok;this.F.I=0;var b=this.F;var c=a.level,d=a.method,e=a.windowBits,f=a.memLevel,g=a.strategy;if(b){var h=1;-1===c&&(c=6);0>e?(h=0,e=-e):15<e&&(h=2,e-=16);if(1>f||9<
f||8!==d||8>e||15<e||0>c||9<c||0>g||4<g)b=Zj(b,-2);else{8===e&&(e=9);var l=new mk;b.state=l;l.F=b;l.wrap=h;l.B=null;l.Sc=e;l.ha=1<<l.Sc;l.Xa=l.ha-1;l.Bc=f+7;l.ec=1<<l.Bc;l.La=l.ec-1;l.Ma=~~((l.Bc+3-1)/3);l.window=new K.nb(2*l.ha);l.head=new K.Ja(l.ec);l.Ha=new K.Ja(l.ha);l.Lb=1<<f+6;l.wa=4*l.Lb;l.S=new K.nb(l.wa);l.Hb=1*l.Lb;l.Fc=3*l.Lb;l.level=c;l.strategy=g;l.method=d;if(b&&b.state){b.kb=b.Qc=0;b.vc=2;c=b.state;c.pending=0;c.Mb=0;0>c.wrap&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.D=2===c.wrap?
0:1;c.vb=0;if(!Xj){d=Array(16);for(f=g=0;28>f;f++)for(Bj[f]=g,e=0;e<1<<tj[f];e++)Aj[g++]=f;Aj[g-1]=f;for(f=g=0;16>f;f++)for(Cj[f]=g,e=0;e<1<<uj[f];e++)zj[g++]=f;for(g>>=7;30>f;f++)for(Cj[f]=g<<7,e=0;e<1<<uj[f]-7;e++)zj[256+g++]=f;for(e=0;15>=e;e++)d[e]=0;for(e=0;143>=e;)xj[2*e+1]=8,e++,d[8]++;for(;255>=e;)xj[2*e+1]=9,e++,d[9]++;for(;279>=e;)xj[2*e+1]=7,e++,d[7]++;for(;287>=e;)xj[2*e+1]=8,e++,d[8]++;Mj(xj,287,d);for(e=0;30>e;e++)yj[2*e+1]=5,yj[2*e]=Lj(e,5);Ej=new Dj(xj,tj,257,286,15);Fj=new Dj(yj,
uj,0,30,15);Gj=new Dj([],vj,0,19,7);Xj=!0}c.fc=new Hj(c.oa,Ej);c.ac=new Hj(c.cb,Fj);c.Xc=new Hj(c.ea,Gj);c.ja=0;c.ba=0;Nj(c);c=0}else c=Zj(b,-2);0===c&&(b=b.state,b.Ld=2*b.ha,ak(b.head),b.Gc=lk[b.level].we,b.jd=lk[b.level].ne,b.sd=lk[b.level].ze,b.qd=lk[b.level].ue,b.o=0,b.ra=0,b.u=0,b.qa=0,b.J=b.ta=2,b.eb=0,b.H=0);b=c}}else b=-2;if(0!==b)throw Error(rj[b]);a.header&&(b=this.F)&&b.state&&2===b.state.wrap&&(b.state.B=a.header);if(a.dictionary){var m;"string"===typeof a.dictionary?m=kj(a.dictionary):
"[object ArrayBuffer]"===pk.call(a.dictionary)?m=new Uint8Array(a.dictionary):m=a.dictionary;a=this.F;f=m;g=f.length;if(a&&a.state)if(m=a.state,b=m.wrap,2===b||1===b&&42!==m.status||m.u)b=-2;else{1===b&&(a.D=lj(a.D,f,g,0));m.wrap=0;g>=m.ha&&(0===b&&(ak(m.head),m.o=0,m.ra=0,m.qa=0),c=new K.nb(m.ha),K.qb(c,f,g-m.ha,m.ha,0),f=c,g=m.ha);c=a.ia;d=a.gb;e=a.input;a.ia=g;a.gb=0;a.input=f;for(fk(m);3<=m.u;){f=m.o;g=m.u-2;do m.H=(m.H<<m.Ma^m.window[f+3-1])&m.La,m.Ha[f&m.Xa]=m.head[m.H],m.head[m.H]=f,f++;while(--g);
m.o=f;m.u=2;fk(m)}m.o+=m.u;m.ra=m.o;m.qa=m.u;m.u=0;m.J=m.ta=2;m.eb=0;a.gb=d;a.input=e;a.ia=c;m.wrap=b;b=0}else b=-2;if(0!==b)throw Error(rj[b]);this.xf=!0}}
qk.prototype.push=function(a,b){var c=this.F,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:!0===b?4:0;"string"===typeof a?c.input=kj(a):"[object ArrayBuffer]"===pk.call(a)?c.input=new Uint8Array(a):c.input=a;c.gb=0;c.ia=c.input.length;do{0===c.I&&(c.output=new K.nb(d),c.yb=0,c.I=d);a=nk(c,e);if(1!==a&&0!==a)return rk(this,a),this.ended=!0,!1;if(0===c.I||0===c.ia&&(4===e||2===e))if("string"===this.options.to){var f=K.Pc(c.output,c.yb);b=f;f=f.length;if(65537>f&&(b.subarray&&jj||!b.subarray))b=
String.fromCharCode.apply(null,K.Pc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=K.Pc(c.output,c.yb),this.chunks.push(b)}while((0<c.ia||0===c.I)&&1!==a);if(4===e)return(c=this.F)&&c.state?(d=c.state.status,42!==d&&69!==d&&73!==d&&91!==d&&103!==d&&113!==d&&666!==d?a=Zj(c,-2):(c.state=null,a=113===d?Zj(c,-3):0)):a=-2,rk(this,a),this.ended=!0,0===a;2===e&&(rk(this,0),c.I=0);return!0};
function rk(a,b){0===b&&(a.result="string"===a.options.to?a.chunks.join(""):K.ed(a.chunks));a.chunks=[];a.err=b;a.msg=a.F.msg}
function sk(a){var b=b||{};b.gzip=!0;b=new qk(b);b.push(a,!0);if(b.err)throw b.msg||rj[b.err];return b.result}
;function tk(a){return Gb(null===a?"null":void 0===a?"undefined":a)}
;function uk(a){this.name=a}
;var vk=new uk("rawColdConfigGroup");var wk=new uk("rawHotConfigGroup");var xk=new uk("commandExecutorCommand");function yk(a){I.call(this,a)}
v(yk,I);function zk(a){I.call(this,a)}
v(zk,I);function Ak(a){I.call(this,a,0,Ak.h)}
v(Ak,I);Ak.h=[2];function Bk(a){I.call(this,a,0,Bk.h)}
v(Bk,I);Bk.prototype.getPlayerType=function(){return ie(Od(this,36),0)};
Bk.prototype.setHomeGroupInfo=function(a){return H(this,Ak,81,a)};
Bk.prototype.clearLocationPlayabilityToken=function(){return F(this,89)};
Bk.h=[9,66,24,32,86,100,101];function Ck(a){I.call(this,a)}
v(Ck,I);Ck.prototype.getKey=function(){return je(this,1)};
Ck.prototype.getValue=function(){return je(this,2===Zd(this,Dk)?2:-1)};
var Dk=[2,3,4,5,6];function Ek(a){I.call(this,a,0,Ek.h)}
v(Ek,I);Ek.h=[15,26,28];function Fk(a){I.call(this,a,0,Fk.h)}
v(Fk,I);Fk.h=[5];function Gk(a){I.call(this,a)}
v(Gk,I);function Hk(a){I.call(this,a,0,Hk.h)}
v(Hk,I);Hk.prototype.setSafetyMode=function(a){return F(this,5,a)};
Hk.h=[12];function Ik(a){I.call(this,a,0,Ik.h)}
v(Ik,I);Ik.h=[12];var Jk=new uk("continuationCommand");var Kk=new uk("signalAction");var Lk=new uk("webCommandMetadata");var Mk=new uk("signalServiceEndpoint");var Nk={rf:"EMBEDDED_PLAYER_MODE_UNKNOWN",nf:"EMBEDDED_PLAYER_MODE_DEFAULT",qf:"EMBEDDED_PLAYER_MODE_PFP",pf:"EMBEDDED_PLAYER_MODE_PFL"};var Ok=new uk("feedbackEndpoint");var Pk={wf:"WEB_DISPLAY_MODE_UNKNOWN",sf:"WEB_DISPLAY_MODE_BROWSER",uf:"WEB_DISPLAY_MODE_MINIMAL_UI",vf:"WEB_DISPLAY_MODE_STANDALONE",tf:"WEB_DISPLAY_MODE_FULLSCREEN"};function Qk(a){I.call(this,a)}
v(Qk,I);Qk.prototype.getKey=function(){return je(this,1)};
Qk.prototype.getValue=function(){return je(this,2)};function Rk(a){I.call(this,a,0,Rk.h)}
v(Rk,I);Rk.h=[4,5];function Sk(a){I.call(this,a)}
v(Sk,I);Sk.prototype.getLineNumber=function(){return ie(Od(this,2),0)};
Sk.prototype.getColumnNumber=function(){return ie(Od(this,3),0)};function Tk(a){I.call(this,a)}
v(Tk,I);var Uk=[2,3,4,5];function Vk(a){I.call(this,a)}
v(Vk,I);Vk.prototype.getMessage=function(){return je(this,1)};
Vk.prototype.getLevel=function(){return ie(Od(this,2),0)};function Wk(a){I.call(this,a)}
v(Wk,I);function Xk(a){I.call(this,a)}
v(Xk,I);function Yk(a){I.call(this,a,0,Yk.h)}
v(Yk,I);Yk.h=[10,17];function Zk(a){I.call(this,a)}
v(Zk,I);function $k(a){I.call(this,a)}
v($k,I);function rl(a){I.call(this,a)}
v(rl,I);function sl(a){I.call(this,a)}
v(sl,I);function tl(a){I.call(this,a)}
v(tl,I);function ul(a){var b=new tl;return F(b,1,a)}
tl.prototype.getId=function(){return je(this,2)};
function vl(a,b){return F(a,2,b)}
;function wl(a){I.call(this,a)}
v(wl,I);function xl(a){I.call(this,a,0,xl.h)}
v(xl,I);xl.prototype.getPlayerType=function(){return ie(Od(this,7),0)};
xl.prototype.setVideoId=function(a){return F(this,19,a)};
function yl(a,b){ee(a,68,tl,b)}
xl.h=[112,83,68];function zl(a){I.call(this,a)}
v(zl,I);function Al(a){I.call(this,a)}
v(Al,I);function Bl(a){I.call(this,a)}
v(Bl,I);function Cl(a){I.call(this,a,475)}
v(Cl,I);
var Dl=[2,3,5,6,7,11,13,20,21,22,23,24,28,32,37,45,59,72,73,74,76,78,79,80,85,91,97,100,102,105,111,117,119,126,127,136,146,148,151,156,157,158,159,163,164,168,176,177,178,179,184,188,189,190,191,193,194,195,196,197,198,199,200,201,202,203,204,205,206,208,209,215,219,222,225,226,227,229,232,233,234,240,241,244,247,248,249,251,254,255,256,257,258,259,260,261,266,270,272,278,288,291,293,300,304,308,309,310,311,313,314,319,320,321,323,324,327,328,330,331,332,334,337,338,340,344,348,350,351,352,353,354,
355,356,357,358,361,363,364,368,369,370,373,374,375,378,380,381,383,388,389,402,403,410,411,412,413,414,415,416,417,418,423,424,425,426,427,429,430,431,439,441,444,448,458,469,471,473,474];function El(a){I.call(this,a)}
v(El,I);function Fl(a){I.call(this,a)}
v(Fl,I);Fl.prototype.setVideoId=function(a){return Yd(this,1,Gl,a)};
Fl.prototype.getPlaylistId=function(){var a=2===Zd(this,Gl)?2:-1;return Od(this,a)};
var Gl=[1,2];function Hl(a){I.call(this,a,0,Hl.h)}
v(Hl,I);Hl.h=[3];var Il=new uk("webPlayerShareEntityServiceEndpoint");var Jl=new uk("playlistEditEndpoint");var Kl=new uk("modifyChannelNotificationPreferenceEndpoint");var Ll=new uk("unsubscribeEndpoint");var Ml=new uk("subscribeEndpoint");function Nl(){var a=Ol;B("yt.ads.biscotti.getId_")||A("yt.ads.biscotti.getId_",a)}
function Pl(a){A("yt.ads.biscotti.lastId_",a)}
;function Ql(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var Rl=x.window,Sl,Tl,Ul=(null==Rl?void 0:null==(Sl=Rl.yt)?void 0:Sl.config_)||(null==Rl?void 0:null==(Tl=Rl.ytcfg)?void 0:Tl.data_)||{};A("yt.config_",Ul);function Vl(){Ql(Ul,arguments)}
function O(a,b){return a in Ul?Ul[a]:b}
function Wl(){var a=Ul.EXPERIMENT_FLAGS;return a?a.web_disable_gel_stp_ecatcher_killswitch:void 0}
;var Xl=[];function Yl(a){Xl.forEach(function(b){return b(a)})}
function Zl(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){$l(b)}}:a}
function $l(a){var b=B("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0,void 0,void 0):(b=O("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0,void 0,void 0]),Vl("ERRORS",b));Yl(a)}
function am(a,b,c,d,e){var f=B("yt.logging.errors.log");f?f(a,"WARNING",b,c,d,void 0,e):(f=O("ERRORS",[]),f.push([a,"WARNING",b,c,d,void 0,e]),Vl("ERRORS",f))}
;var bm=/^[\w.]*$/,cm={q:!0,search_query:!0};function dm(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=em(f[0]||""),h=em(f[1]||"");g in c?Array.isArray(c[g])?lb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(r){var l=r,m=f[0],p=String(dm);l.args=[{key:m,value:f[1],query:a,method:fm==p?"unchanged":p}];cm.hasOwnProperty(m)||am(l)}}return c}
var fm=String(dm);function gm(a){var b=[];mb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];gb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function hm(a){"?"==a.charAt(0)&&(a=a.substr(1));return dm(a,"&")}
function im(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),hm(1<a.length?a[1]:a[0])):{}}
function jm(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=hm(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return Ec(a,e)+d}
function km(a){if(!b)var b=window.location.href;var c=wc(1,a),d=xc(a);c&&d?(a=a.match(uc),b=b.match(uc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?xc(b)==d&&(Number(wc(4,b))||null)==(Number(wc(4,a))||null):!0;return a}
function em(a){return a&&a.match(bm)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function lm(a){var b=mm;a=void 0===a?B("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=ki;e.flash="0";a:{try{var f=b.h.top.location.href}catch(ma){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?Ph:g;try{var h=g.history.length}catch(ma){h=0}e.u_his=h;var l;e.u_h=null==(l=Ph.screen)?void 0:l.height;var m;e.u_w=null==(m=Ph.screen)?void 0:m.width;var p;e.u_ah=null==(p=Ph.screen)?void 0:p.availHeight;var r;e.u_aw=
null==(r=Ph.screen)?void 0:r.availWidth;var y;e.u_cd=null==(y=Ph.screen)?void 0:y.colorDepth}catch(ma){}h=b.h;try{var u=h.screenX;var z=h.screenY}catch(ma){}try{var D=h.outerWidth;var G=h.outerHeight}catch(ma){}try{var M=h.innerWidth;var P=h.innerHeight}catch(ma){}try{var T=h.screenLeft;var da=h.screenTop}catch(ma){}try{M=h.innerWidth,P=h.innerHeight}catch(ma){}try{var Z=h.screen.availWidth;var na=h.screen.availTop}catch(ma){}u=[T,da,u,z,Z,na,D,G,M,P];try{var La=(b.h.top||window).document,ya="CSS1Compat"==
La.compatMode?La.documentElement:La.body;var za=(new rf(ya.clientWidth,ya.clientHeight)).round()}catch(ma){za=new rf(-12245933,-12245933)}La=za;za={};var va=void 0===va?x:va;ya=new ti;"SVGElement"in va&&"createElementNS"in va.document&&ya.set(0);z=hi();z["allow-top-navigation-by-user-activation"]&&ya.set(1);z["allow-popups-to-escape-sandbox"]&&ya.set(2);va.crypto&&va.crypto.subtle&&ya.set(3);"TextDecoder"in va&&"TextEncoder"in va&&ya.set(4);va=ui(ya);za.bc=va;za.bih=La.height;za.biw=La.width;za.brdim=
u.join();b=b.i;b=(za.vis=b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,za.wgl=!!Ph.WebGLRenderingContext,za);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var mm=new function(){var a=window.document;this.h=window;this.i=a};
A("yt.ads_.signals_.getAdSignalsString",function(a){return gm(lm(a))});Date.now();navigator.userAgent.indexOf(" (CrKey ");function R(a){a=nm(a);return"string"===typeof a&&"false"===a?!1:!!a}
function om(a,b){a=nm(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function pm(){return O("EXPERIMENTS_TOKEN","")}
function nm(a){var b=O("EXPERIMENTS_FORCED_FLAGS",{})||{};return void 0!==b[a]?b[a]:O("EXPERIMENT_FLAGS",{})[a]}
function qm(){for(var a=[],b=O("EXPERIMENTS_FORCED_FLAGS",{}),c=t(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=O("EXPERIMENT_FLAGS",{});var e=t(Object.keys(c));for(d=e.next();!d.done;d=e.next())d=d.value,d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var rm="XMLHttpRequest"in x?function(){return new XMLHttpRequest}:null;
function sm(){if(!rm)return null;var a=rm();return"open"in a?a:null}
function tm(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function um(a,b){"function"===typeof a&&(a=Zl(a));return window.setTimeout(a,b)}
;var wm={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},xm="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ia(li)),ym=!1;
function zm(a,b){b=void 0===b?{}:b;var c=km(a),d=R("web_ajax_ignore_global_headers_if_set"),e;for(e in wm){var f=O(wm[e]);"X-Goog-Visitor-Id"!==e||f||(f=O("VISITOR_DATA"));!f||!c&&xc(a)||d&&void 0!==b[e]||!(R("move_vss_away_from_login_info_cookie")||"X-Goog-AuthUser"!==e&&"X-Goog-PageId"!==e)||(b[e]=f)}R("move_vss_away_from_login_info_cookie")&&c&&O("SESSION_INDEX")&&(b["X-Yt-Auth-Test"]="test");"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!xc(a))b["X-YouTube-Utc-Offset"]=
String(-(new Date).getTimezoneOffset());if(c||!xc(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&xc(a)||(b["X-YouTube-Ad-Signals"]=gm(lm()));return b}
function Am(a){var b=window.location.search,c=xc(a);R("debug_handle_relative_url_for_query_forward_killswitch")||!c&&km(a)&&(c=document.location.hostname);var d=vc(wc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=hm(b),f={};gb(xm,function(g){e[g]&&(f[g]=e[g])});
return jm(a,f||{},!1)}
function Bm(a,b){var c=b.format||"JSON";a=Cm(a,b);var d=Dm(a,b),e=!1,f=Em(a,function(l){if(!e){e=!0;h&&window.clearTimeout(h);var m=tm(l),p=null,r=400<=l.status&&500>l.status,y=500<=l.status&&600>l.status;if(m||r||y)p=Fm(a,c,l,b.convertToSafeHtml);if(m)a:if(l&&204==l.status)m=!0;else{switch(c){case "XML":m=0==parseInt(p&&p.return_code,10);break a;case "RAW":m=!0;break a}m=!!p}p=p||{};r=b.context||x;m?b.onSuccess&&b.onSuccess.call(r,l,p):b.onError&&b.onError.call(r,l,p);b.onFinish&&b.onFinish.call(r,
l,p)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=um(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||x,f))},d)}return f}
function Cm(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=O("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=jm(a,b||{},!0);return a}
function Dm(a,b){var c=O("XSRF_FIELD_NAME"),d=O("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=O("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||xc(a)&&!b.withCredentials&&xc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(R("ajax_parse_query_data_only_when_filled")&&f&&0<Object.keys(f).length||f)&&"string"===typeof e&&(e=hm(e),vb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?
JSON.stringify(e):Cc(e));if(!(a=e)&&(a=f)){a:{for(var l in f){f=!1;break a}f=!0}a=!f}!ym&&a&&"POST"!=b.method&&(ym=!0,$l(Error("AJAX request with postData should use POST")));return e}
function Fm(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,am(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Gm(a):null)e={},gb(a.getElementsByTagName("*"),function(g){e[g.tagName]=Hm(g)})}d&&Im(e);
return e}
function Im(a){if(Sa(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b],e=xb();d=e?e.createHTML(d):d;a[c]=new mc(d)}else Im(a[b])}}
function Gm(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Hm(a){var b="";gb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Jm(a,b){b.method="POST";b.postParams||(b.postParams={});return Bm(a,b)}
function Em(a,b,c,d,e,f,g){function h(){4==(l&&"readyState"in l?l.readyState:0)&&b&&Zl(b)(l)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var l=sm();if(!l)return null;"onloadend"in l?l.addEventListener("loadend",h,!1):l.onreadystatechange=h;R("debug_forward_web_query_parameters")&&(a=Am(a));l.open(c,a,!0);f&&(l.responseType=f);g&&(l.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=zm(a,e))for(var m in e)l.setRequestHeader(m,e[m]),"content-type"==m.toLowerCase()&&(c=!1);c&&l.setRequestHeader("Content-Type","application/x-www-form-urlencoded");l.send(d);
return l}
;var Km=[{Hc:function(a){return"Cannot read property '"+a.key+"'"},
ic:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Hc:function(a){return"Cannot call '"+a.key+"'"},
ic:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Hc:function(a){return a.key+" is not defined"},
ic:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Mm={Va:[],Sa:[{callback:Lm,weight:500}]};function Lm(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Nm(){this.Sa=[];this.Va=[]}
var Om;function Pm(){if(!Om){var a=Om=new Nm;a.Va.length=0;a.Sa.length=0;Mm.Va&&a.Va.push.apply(a.Va,Mm.Va);Mm.Sa&&a.Sa.push.apply(a.Sa,Mm.Sa)}return Om}
;var Qm=new Pi;function Rm(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Sm(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=Sm(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=Sm(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function Sm(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Tm(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Um(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=Rm(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?Um(e+".ve",f,g,h):0;d+=g;d+=Um(e,a[e],b,c);if(500<d)break}}else c[b]=Vm(a),d+=c[b].length;else c[b]=Vm(a),d+=c[b].length;return d}
function Um(a,b,c,d){c+="."+a;a=Vm(b);d[c]=a;return c.length+a.length}
function Vm(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function Wm(){this.Ve=!0}
function Xm(){Wm.h||(Wm.h=new Wm);return Wm.h}
function Ym(a,b){a={};var c=Ig([]);c&&(a.Authorization=c,c=b=null==b?void 0:b.sessionIndex,void 0===c&&(c=Number(O("SESSION_INDEX",0)),c=isNaN(c)?0:c),R("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in Ul||(a["X-Origin"]=window.location.origin),void 0===b&&"DELEGATED_SESSION_ID"in Ul&&(a["X-Goog-PageId"]=O("DELEGATED_SESSION_ID")));return a}
;var Zm={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function $m(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function an(){if(!x.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return x.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":x.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":x.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":x.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function bn(a,b,c,d,e){Eg.set(""+a,b,{hc:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function cn(a,b,c){Eg.remove(""+a,void 0===b?"/":b,void 0===c?"youtube.com":c)}
function dn(){if(!Eg.isEnabled())return!1;if(!Eg.isEmpty())return!0;Eg.set("TESTCOOKIESENABLED","1",{hc:60});if("1"!==Eg.get("TESTCOOKIESENABLED"))return!1;Eg.remove("TESTCOOKIESENABLED");return!0}
;var en=B("ytglobal.prefsUserPrefsPrefs_")||{};A("ytglobal.prefsUserPrefsPrefs_",en);function fn(){this.h=O("ALT_PREF_COOKIE_NAME","PREF");this.i=O("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=Eg.get(""+this.h,void 0);a&&this.parse(a)}
var gn;function hn(){gn||(gn=new fn);return gn}
k=fn.prototype;k.get=function(a,b){jn(a);kn(a);a=void 0!==en[a]?en[a].toString():null;return null!=a?a:b?b:""};
k.set=function(a,b){jn(a);kn(a);if(null==b)throw Error("ExpectedNotNull");en[a]=b.toString()};
function ln(a){return!!((mn("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
k.remove=function(a){jn(a);kn(a);delete en[a]};
k.clear=function(){for(var a in en)delete en[a]};
function kn(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function jn(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function mn(a){a=void 0!==en[a]?en[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
k.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(en[d]=c.toString())}};var nn={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},on={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},pn={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},qn={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function rn(){var a=x.navigator;return a?a.connection:void 0}
function sn(){var a=rn();if(a){var b=nn[a.type||"unknown"]||"CONN_UNKNOWN";a=nn[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function tn(){var a=rn();if(null!=a&&a.effectiveType)return qn.hasOwnProperty(a.effectiveType)?qn[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function un(a){var b=Ma.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ia(b))}
v(un,Error);function vn(){try{return wn(),!0}catch(a){return!1}}
function wn(a){if(void 0!==O("DATASYNC_ID"))return O("DATASYNC_ID");throw new un("Datasync ID not set",void 0===a?"unknown":a);}
;function xn(){}
function yn(a,b){return zn(a,0,b)}
xn.prototype.ma=function(a,b){return zn(a,1,b)};
function An(a){var b=B("yt.scheduler.instance.addImmediateJob");b?b(a):a()}
;function Bn(){xn.apply(this,arguments)}
v(Bn,xn);function Cn(){Bn.h||(Bn.h=new Bn);return Bn.h}
function zn(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=B("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):um(a,c||0)}
Bn.prototype.Fa=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=B("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
Bn.prototype.start=function(){var a=B("yt.scheduler.instance.start");a&&a()};
Bn.prototype.pause=function(){var a=B("yt.scheduler.instance.pause");a&&a()};
var si=Cn();function Dn(a){var b=new $i;(b=b.isAvailable()?a?new fj(b,a):b:null)||(a=new aj(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new Wi(a):null;this.i=document.domain||window.location.hostname}
Dn.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape((new Lg).serialize(b))}catch(f){return}else e=escape(b);bn(a,e,c,this.i)};
Dn.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Eg.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Dn.prototype.remove=function(a){this.h&&this.h.remove(a);cn(a,"/",this.i)};var En=function(){var a;return function(){a||(a=new Dn("ytidb"));return a}}();
function Fn(){var a;return null==(a=En())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var Gn=[],Hn,In=!1;function Jn(){var a={};for(Hn=new Kn(void 0===a.handleError?Ln:a.handleError,void 0===a.logEvent?Mn:a.logEvent);0<Gn.length;)switch(a=Gn.shift(),a.type){case "ERROR":Hn.handleError(a.payload);break;case "EVENT":Hn.logEvent(a.eventType,a.payload)}}
function Nn(a){In||(Hn?Hn.handleError(a):(Gn.push({type:"ERROR",payload:a}),10<Gn.length&&Gn.shift()))}
function On(a,b){In||(Hn?Hn.logEvent(a,b):(Gn.push({type:"EVENT",eventType:a,payload:b}),10<Gn.length&&Gn.shift()))}
;function Pn(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function Qn(a){return a.substr(0,a.indexOf(":"))||a}
;var Rn=od||pd;function Sn(a){var b=Wb();return b?0<=b.toLowerCase().indexOf(a):!1}
;var Tn={},Un=(Tn.AUTH_INVALID="No user identifier specified.",Tn.EXPLICIT_ABORT="Transaction was explicitly aborted.",Tn.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Tn.MISSING_INDEX="Index not created.",Tn.MISSING_OBJECT_STORES="Object stores not created.",Tn.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",Tn.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",Tn.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
Tn.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",Tn.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Tn.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",Tn.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",Tn),Vn={},Wn=(Vn.AUTH_INVALID="ERROR",Vn.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",Vn.EXPLICIT_ABORT="IGNORED",Vn.IDB_NOT_SUPPORTED="ERROR",Vn.MISSING_INDEX=
"WARNING",Vn.MISSING_OBJECT_STORES="ERROR",Vn.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",Vn.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",Vn.QUOTA_EXCEEDED="WARNING",Vn.QUOTA_MAYBE_EXCEEDED="WARNING",Vn.UNKNOWN_ABORT="WARNING",Vn.INCOMPATIBLE_DB_VERSION="WARNING",Vn),Xn={},Yn=(Xn.AUTH_INVALID=!1,Xn.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,Xn.EXPLICIT_ABORT=!1,Xn.IDB_NOT_SUPPORTED=!1,Xn.MISSING_INDEX=!1,Xn.MISSING_OBJECT_STORES=!1,Xn.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,Xn.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,Xn.QUOTA_EXCEEDED=!1,Xn.QUOTA_MAYBE_EXCEEDED=!0,Xn.UNKNOWN_ABORT=!0,Xn.INCOMPATIBLE_DB_VERSION=!1,Xn);function Zn(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?Un[a]:c;d=void 0===d?Wn[a]:d;e=void 0===e?Yn[a]:e;un.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,Zn.prototype)}
v(Zn,un);function $n(a,b){Zn.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},Un.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,$n.prototype)}
v($n,Zn);function ao(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,ao.prototype)}
v(ao,Error);var bo=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function co(a,b,c,d){b=Qn(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof Zn)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new Zn("QUOTA_EXCEEDED",a);if(qd&&"UnknownError"===e.name)return new Zn("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof ao)return new Zn("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&bo.some(function(f){return e.message.includes(f)}))return new Zn("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new Zn("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",ud:e.name})];e.level="WARNING";return e}
function eo(a,b,c){var d=Fn();return new Zn("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function fo(a){if(!a)throw Error();throw a;}
function go(a){return a}
function ho(a){this.h=a}
function io(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=t(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=t(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
io.all=function(a){return new io(new ho(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={lb:0};f.lb<a.length;f={lb:f.lb},++f.lb)io.resolve(a[f.lb]).then(function(g){return function(h){d[g.lb]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
io.resolve=function(a){return new io(new ho(function(b,c){a instanceof io?a.then(b,c):b(a)}))};
io.reject=function(a){return new io(new ho(function(b,c){c(a)}))};
io.prototype.then=function(a,b){var c=this,d=null!=a?a:go,e=null!=b?b:fo;return new io(new ho(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){jo(c,c,d,f,g)}),c.i.push(function(){ko(c,c,e,f,g)})):"FULFILLED"===c.state.status?jo(c,c,d,f,g):"REJECTED"===c.state.status&&ko(c,c,e,f,g)}))};
io.prototype.catch=function(a){return this.then(void 0,a)};
function jo(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof io?lo(a,b,f,d,e):d(f)}catch(g){e(g)}}
function ko(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof io?lo(a,b,f,d,e):d(f)}catch(g){e(g)}}
function lo(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof io?lo(a,b,f,d,e):d(f)},function(f){e(f)})}
;function mo(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function no(a){return new Promise(function(b,c){mo(a,b,c)})}
function oo(a){return new io(new ho(function(b,c){mo(a,b,c)}))}
;function po(a,b){return new io(new ho(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var qo=window,S=qo.ytcsi&&qo.ytcsi.now?qo.ytcsi.now:qo.performance&&qo.performance.timing&&qo.performance.now&&qo.performance.timing.navigationStart?function(){return qo.performance.timing.navigationStart+qo.performance.now()}:function(){return(new Date).getTime()};function ro(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(S());this.i=!1}
k=ro.prototype;k.add=function(a,b,c){return so(this,[a],{mode:"readwrite",fa:!0},function(d){return d.objectStore(a).add(b,c)})};
k.clear=function(a){return so(this,[a],{mode:"readwrite",fa:!0},function(b){return b.objectStore(a).clear()})};
k.close=function(){this.h.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
k.count=function(a,b){return so(this,[a],{mode:"readonly",fa:!0},function(c){return c.objectStore(a).count(b)})};
function to(a,b,c){a=a.h.createObjectStore(b,c);return new uo(a)}
k.delete=function(a,b){return so(this,[a],{mode:"readwrite",fa:!0},function(c){return c.objectStore(a).delete(b)})};
k.get=function(a,b){return so(this,[a],{mode:"readonly",fa:!0},function(c){return c.objectStore(a).get(b)})};
function vo(a,b,c){return so(a,[b],{mode:"readwrite",fa:!0},function(d){d=d.objectStore(b);return oo(d.h.put(c,void 0))})}
k.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function so(a,b,c,d){var e,f,g,h,l,m,p,r,y,u,z,D;return w(function(G){switch(G.h){case 1:var M={mode:"readonly",fa:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?M.mode=c:Object.assign(M,c);e=M;a.transactionCount++;f=e.fa?3:1;g=0;case 2:if(h){G.A(3);break}g++;l=Math.round(S());Aa(G,4);m=a.h.transaction(b,e.mode);M=G.yield;var P=new wo(m);P=xo(P,d);return M.call(G,P,6);case 6:return p=G.i,r=Math.round(S()),yo(a,l,r,g,void 0,b.join(),e),G.return(p);case 4:y=Ca(G);u=Math.round(S());z=co(y,
a.h.name,b.join(),a.h.version);if((D=z instanceof Zn&&!z.h)||g>=f)yo(a,l,u,g,z,b.join(),e),h=z;G.A(2);break;case 3:return G.return(Promise.reject(h))}})}
function yo(a,b,c,d,e,f,g){b=c-b;e?(e instanceof Zn&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&On("QUOTA_EXCEEDED",{dbName:Qn(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof Zn&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),On("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),zo(a,!1,d,f,b,g.tag),Nn(e)):zo(a,!0,d,f,b,g.tag)}
function zo(a,b,c,d,e,f){On("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
k.getName=function(){return this.h.name};
function uo(a){this.h=a}
k=uo.prototype;k.add=function(a,b){return oo(this.h.add(a,b))};
k.autoIncrement=function(){return this.h.autoIncrement};
k.clear=function(){return oo(this.h.clear()).then(function(){})};
function Ao(a,b,c){a.h.createIndex(b,c,{unique:!1})}
k.count=function(a){return oo(this.h.count(a))};
function Bo(a,b){return Co(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
k.delete=function(a){return a instanceof IDBKeyRange?Bo(this,a):oo(this.h.delete(a))};
k.get=function(a){return oo(this.h.get(a))};
k.index=function(a){try{return new Do(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new ao(a,this.h.name);throw b;}};
k.getName=function(){return this.h.name};
k.keyPath=function(){return this.h.keyPath};
function Co(a,b,c){a=a.h.openCursor(b.query,b.direction);return Eo(a).then(function(d){return po(d,c)})}
function wo(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=Zn;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var l=f.item(h);if(null===l)throw Error("Invariant: item in DOMStringList is null");g.push(l)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function xo(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return t(d).next().value})}
wo.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new Zn("EXPLICIT_ABORT");};
wo.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.i.get(a);b||(b=new uo(a),this.i.set(a,b));return b};
function Do(a){this.h=a}
k=Do.prototype;k.count=function(a){return oo(this.h.count(a))};
k.delete=function(a){return Fo(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
k.get=function(a){return oo(this.h.get(a))};
k.getKey=function(a){return oo(this.h.getKey(a))};
k.keyPath=function(){return this.h.keyPath};
k.unique=function(){return this.h.unique};
function Fo(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Eo(a).then(function(d){return po(d,c)})}
function Go(a,b){this.request=a;this.cursor=b}
function Eo(a){return oo(a).then(function(b){return b?new Go(a,b):null})}
k=Go.prototype;k.advance=function(a){this.cursor.advance(a);return Eo(this.request)};
k.continue=function(a){this.cursor.continue(a);return Eo(this.request)};
k.delete=function(){return oo(this.cursor.delete()).then(function(){})};
k.getKey=function(){return this.cursor.key};
k.getValue=function(){return this.cursor.value};
k.update=function(a){return oo(this.cursor.update(a))};function Ho(a,b,c){return new Promise(function(d,e){function f(){y||(y=new ro(g.result,{closed:r}));return y}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.Vd,l=c.blocking,m=c.We,p=c.upgrade,r=c.closed,y;g.addEventListener("upgradeneeded",function(u){try{if(null===u.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");u.dataLoss&&"none"!==u.dataLoss&&On("IDB_DATA_CORRUPTED",{reason:u.dataLossMessage||"unknown reason",dbName:Qn(a)});var z=f(),D=new wo(g.transaction);
p&&p(z,function(G){return u.oldVersion<G&&u.newVersion>=G},D);
D.done.catch(function(G){e(G)})}catch(G){e(G)}});
g.addEventListener("success",function(){var u=g.result;l&&u.addEventListener("versionchange",function(){l(f())});
u.addEventListener("close",function(){On("IDB_UNEXPECTEDLY_CLOSED",{dbName:Qn(a),dbVersion:u.version});m&&m()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Io(a,b,c){c=void 0===c?{}:c;return Ho(a,b,c)}
function Jo(a,b){b=void 0===b?{}:b;var c,d,e,f;return w(function(g){if(1==g.h)return Aa(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.Vd)&&c.addEventListener("blocked",function(){e()}),g.yield(no(c),4);
if(2!=g.h)return Ba(g,0);f=Ca(g);throw co(f,a,"",-1);})}
;function Ko(a,b){this.name=a;this.options=b;this.j=!0;this.m=this.l=0}
Ko.prototype.i=function(a,b,c){c=void 0===c?{}:c;return Io(a,b,c)};
Ko.prototype.delete=function(a){a=void 0===a?{}:a;return Jo(this.name,a)};
function Lo(a,b){return new Zn("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function Mo(a,b){if(!b)throw eo("openWithToken",Qn(a.name));return a.open()}
Ko.prototype.open=function(){function a(){var f,g,h,l,m,p,r,y,u,z;return w(function(D){switch(D.h){case 1:return g=null!=(f=Error().stack)?f:"",Aa(D,2),D.yield(c.i(c.name,c.options.version,e),4);case 4:h=D.i;for(var G=c.options,M=[],P=t(Object.keys(G.zb)),T=P.next();!T.done;T=P.next()){T=T.value;var da=G.zb[T],Z=void 0===da.Ee?Number.MAX_VALUE:da.Ee;!(h.h.version>=da.Gb)||h.h.version>=Z||h.h.objectStoreNames.contains(T)||M.push(T)}l=M;if(0===l.length){D.A(5);break}m=Object.keys(c.options.zb);p=h.objectStoreNames();
if(c.m<om("ytidb_reopen_db_retries",0))return c.m++,h.close(),Nn(new Zn("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:m,foundObjectStores:p})),D.return(a());if(!(c.l<om("ytidb_remake_db_retries",1))){D.A(6);break}c.l++;return D.yield(c.delete(),7);case 7:return Nn(new Zn("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:m,foundObjectStores:p})),D.return(a());case 6:throw new $n(p,m);case 5:return D.return(h);case 2:r=Ca(D);if(r instanceof DOMException?
"VersionError"!==r.name:"DOMError"in self&&r instanceof DOMError?"VersionError"!==r.name:!(r instanceof Object&&"message"in r)||"An attempt was made to open a database using a lower version than the existing version."!==r.message){D.A(8);break}return D.yield(c.i(c.name,void 0,Object.assign({},e,{upgrade:void 0})),9);case 9:y=D.i;u=y.h.version;if(void 0!==c.options.version&&u>c.options.version+1)throw y.close(),c.j=!1,Lo(c,u);return D.return(y);case 8:throw b(),r instanceof Error&&!R("ytidb_async_stack_killswitch")&&
(r.stack=r.stack+"\n"+g.substring(g.indexOf("\n")+1)),co(r,c.name,"",null!=(z=c.options.version)?z:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.j)throw Lo(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,We:b,upgrade:this.options.upgrade};return this.h=d=a()};var No=new Ko("YtIdbMeta",{zb:{databases:{Gb:1}},upgrade:function(a,b){b(1)&&to(a,"databases",{keyPath:"actualName"})}});
function Oo(a,b){var c;return w(function(d){if(1==d.h)return d.yield(Mo(No,b),2);c=d.i;return d.return(so(c,["databases"],{fa:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return oo(f.h.put(a,void 0)).then(function(){})})}))})}
function Po(a,b){var c;return w(function(d){if(1==d.h)return a?d.yield(Mo(No,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function Qo(a,b){var c,d;return w(function(e){return 1==e.h?(c=[],e.yield(Mo(No,b),2)):3!=e.h?(d=e.i,e.yield(so(d,["databases"],{fa:!0,mode:"readonly"},function(f){c.length=0;return Co(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function Ro(a){return Qo(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function So(a,b,c){return Qo(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function To(a){var b,c;return w(function(d){if(1==d.h)return b=wn("YtIdbMeta hasAnyMeta other"),d.yield(Qo(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(0<c.length)})}
;var Uo,Vo=new function(){}(new function(){});
function Wo(){var a,b,c,d;return w(function(e){switch(e.h){case 1:a=Fn();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=Rn)f=/WebKit\/([0-9]+)/.exec(Wb()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Wb()),f=!(f&&602<=parseInt(f[1],10)));if(f||ad)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
Aa(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return e.yield(Oo(d,Vo),4);case 4:return e.yield(Po("yt-idb-test-do-not-use",Vo),5);case 5:return e.return(!0);case 2:return Ca(e),e.return(!1)}})}
function Xo(){if(void 0!==Uo)return Uo;In=!0;return Uo=Wo().then(function(a){In=!1;var b;if(null!=(b=En())&&b.h){var c;b={hasSucceededOnce:(null==(c=Fn())?void 0:c.hasSucceededOnce)||a};var d;null==(d=En())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function Yo(){return B("ytglobal.idbToken_")||void 0}
function Zo(){var a=Yo();return a?Promise.resolve(a):Xo().then(function(b){(b=b?Vo:void 0)&&A("ytglobal.idbToken_",b);return b})}
;var $o=0;function ap(a,b){$o||($o=si.ma(function(){var c,d,e,f,g;return w(function(h){switch(h.h){case 1:return h.yield(Zo(),2);case 2:c=h.i;if(!c)return h.return();d=!0;Aa(h,3);return h.yield(So(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.A(6);break}f=e[0];return h.yield(Jo(f.actualName),7);case 7:return h.yield(Po(f.actualName,c),6);case 6:Ba(h,4);break;case 3:g=Ca(h),Nn(g),d=!1;case 4:si.Fa($o),$o=0,d&&ap(a,b),h.h=0}})}))}
function bp(){var a;return w(function(b){return 1==b.h?b.yield(Zo(),2):(a=b.i)?b.return(To(a)):b.return(!1)})}
new Nh;function cp(a){if(!vn())throw a=new Zn("AUTH_INVALID",{dbName:a}),Nn(a),a;var b=wn();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function dp(a,b,c,d){var e,f,g,h,l,m;return w(function(p){switch(p.h){case 1:return f=null!=(e=Error().stack)?e:"",p.yield(Zo(),2);case 2:g=p.i;if(!g)throw h=eo("openDbImpl",a,b),R("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),Nn(h),h;Pn(a);l=c?{actualName:a,publicName:a,userIdentifier:void 0}:cp(a);Aa(p,3);return p.yield(Oo(l,g),5);case 5:return p.yield(Io(l.actualName,b,d),6);case 6:return p.return(p.i);case 3:return m=Ca(p),Aa(p,7),p.yield(Po(l.actualName,
g),9);case 9:Ba(p,8);break;case 7:Ca(p);case 8:throw m;}})}
function ep(a,b,c){c=void 0===c?{}:c;return dp(a,b,!1,c)}
function fp(a,b,c){c=void 0===c?{}:c;return dp(a,b,!0,c)}
function gp(a,b){b=void 0===b?{}:b;var c,d;return w(function(e){if(1==e.h)return e.yield(Zo(),2);if(3!=e.h){c=e.i;if(!c)return e.return();Pn(a);d=cp(a);return e.yield(Jo(d.actualName,b),3)}return e.yield(Po(d.actualName,c),0)})}
function hp(a,b,c){a=a.map(function(d){return w(function(e){return 1==e.h?e.yield(Jo(d.actualName,b),2):e.yield(Po(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function ip(){var a=void 0===a?{}:a;var b,c;return w(function(d){if(1==d.h)return d.yield(Zo(),2);if(3!=d.h){b=d.i;if(!b)return d.return();Pn("LogsDatabaseV2");return d.yield(Ro(b),3)}c=d.i;return d.yield(hp(c,a,b),0)})}
function jp(a,b){b=void 0===b?{}:b;var c;return w(function(d){if(1==d.h)return d.yield(Zo(),2);if(3!=d.h){c=d.i;if(!c)return d.return();Pn(a);return d.yield(Jo(a,b),3)}return d.yield(Po(a,c),0)})}
;function kp(a,b){Ko.call(this,a,b);this.options=b;Pn(a)}
v(kp,Ko);function lp(a,b){var c;return function(){c||(c=new kp(a,b));return c}}
kp.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.nc?fp:ep)(a,b,Object.assign({},c))};
kp.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.nc?jp:gp)(this.name,a)};
function mp(a,b){return lp(a,b)}
;var np={},op=mp("ytGcfConfig",{zb:(np.coldConfigStore={Gb:1},np.hotConfigStore={Gb:1},np),nc:!1,upgrade:function(a,b){b(1)&&(Ao(to(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),Ao(to(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function pp(a){return Mo(op(),a)}
function qp(a,b,c){var d,e,f;return w(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:S()},g.yield(pp(c),2);case 2:return e=g.i,g.yield(e.clear("hotConfigStore"),3);case 3:return g.yield(vo(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function rp(a,b,c,d){var e,f,g;return w(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:S()},h.yield(pp(d),2);case 2:return f=h.i,h.yield(f.clear("coldConfigStore"),3);case 3:return h.yield(vo(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function sp(a){var b,c;return w(function(d){return 1==d.h?d.yield(pp(a),2):3!=d.h?(b=d.i,c=void 0,d.yield(so(b,["coldConfigStore"],{mode:"readwrite",fa:!0},function(e){return Fo(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function tp(a){var b,c;return w(function(d){return 1==d.h?d.yield(pp(a),2):3!=d.h?(b=d.i,c=void 0,d.yield(so(b,["hotConfigStore"],{mode:"readwrite",fa:!0},function(e){return Fo(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function up(){J.apply(this,arguments);this.i=[]}
v(up,J);up.prototype.K=function(){this.i.length=0;J.prototype.K.call(this)};function vp(){this.h=0;this.i=new up}
function wp(a,b,c){var d,e,f;return w(function(g){switch(g.h){case 1:if(!R("update_log_event_config")){g.A(0);break}c&&(a.j=c,A("yt.gcf.config.hotConfigGroup",a.j));a.hotHashData=b;A("yt.gcf.config.hotHashData",a.hotHashData);d=Yo();if(!d){g.A(3);break}if(c){g.A(4);break}return g.yield(tp(d),5);case 5:e=g.i,c=null==(f=e)?void 0:f.config;case 4:return g.yield(qp(c,b,d),3);case 3:if(c)for(var h=c,l=t(a.i.i),m=l.next();!m.done;m=l.next())m=m.value,m(h);g.h=0}})}
function xp(a,b,c){var d,e,f,g;return w(function(h){if(1==h.h){if(!R("update_log_event_config"))return h.A(0);a.coldHashData=b;A("yt.gcf.config.coldHashData",a.coldHashData);return(d=Yo())?c?h.A(4):h.yield(sp(d),5):h.A(0)}4!=h.h&&(e=h.i,c=null==(f=e)?void 0:f.config);if(!c)return h.A(0);g=c.configData;return h.yield(rp(c,b,g,d),0)})}
;function yp(){return"INNERTUBE_API_KEY"in Ul&&"INNERTUBE_API_VERSION"in Ul}
function zp(){return{innertubeApiKey:O("INNERTUBE_API_KEY"),innertubeApiVersion:O("INNERTUBE_API_VERSION"),Cc:O("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),ld:O("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),oe:O("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:O("INNERTUBE_CONTEXT_CLIENT_VERSION"),nd:O("INNERTUBE_CONTEXT_HL"),md:O("INNERTUBE_CONTEXT_GL"),pe:O("INNERTUBE_HOST_OVERRIDE")||"",re:!!O("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),qe:!!O("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:O("SERIALIZED_CLIENT_CONFIG_DATA")}}
function Ap(a){var b={client:{hl:a.nd,gl:a.md,clientName:a.ld,clientVersion:a.innertubeContextClientVersion,configInfo:a.Cc}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=x.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=pm();""!==c&&(b.client.experimentsToken=c);c=qm();0<c.length&&(b.request={internalExperimentFlags:c});Bp(a,void 0,b);Cp(void 0,b);Dp(void 0,b);Ep(a,void 0,b);Fp(void 0,b);R("start_sending_config_hash")&&Gp(void 0,b);O("DELEGATED_SESSION_ID")&&
!R("pageid_as_header_web")&&(b.user={onBehalfOfUser:O("DELEGATED_SESSION_ID")});!R("fill_delegate_context_in_gel_killswitch")&&(a=O("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&(b.user=Object.assign({},b.user,{serializedDelegationContext:a}));a=Object;c=a.assign;for(var d=b.client,e={},f=t(Object.entries(hm(O("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=t(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===
g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function Hp(a){var b=new Ik,c=new Bk;F(c,1,a.nd);F(c,2,a.md);F(c,16,a.oe);F(c,17,a.innertubeContextClientVersion);if(a.Cc){var d=a.Cc,e=new yk;d.coldConfigData&&F(e,1,d.coldConfigData);d.appInstallData&&F(e,6,d.appInstallData);d.coldHashData&&F(e,3,d.coldHashData);d.hotHashData&&F(e,5,d.hotHashData);H(c,yk,62,e)}(d=x.devicePixelRatio)&&1!=d&&F(c,65,Jd(d));d=pm();""!==d&&F(c,54,d);d=qm();if(0<d.length){e=new Ek;for(var f=0;f<d.length;f++){var g=new Ck;F(g,1,d[f].key);Yd(g,2,Dk,d[f].value);ee(e,15,
Ck,g)}H(b,Ek,5,e)}Bp(a,c);Cp(b);Dp(c);Ep(a,c);Fp(c);R("start_sending_config_hash")&&Gp(c);O("DELEGATED_SESSION_ID")&&!R("pageid_as_header_web")&&(a=new Hk,F(a,3,O("DELEGATED_SESSION_ID")));!R("fill_delegate_context_in_gel_killswitch")&&(a=O("INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT"))&&(d=$d(b,Hk,3)||new Hk,a=F(d,18,a),H(b,Hk,3,a));a=t(Object.entries(hm(O("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=t(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?F(c,12,e):"cmodel"===d?F(c,
13,e):"cbr"===d?F(c,87,e):"cbrver"===d?F(c,88,e):"cos"===d?F(c,18,e):"cosver"===d?F(c,19,e):"cplatform"===d&&F(c,42,e);H(b,Bk,1,c);return b}
function Bp(a,b,c){a=a.ld;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=$d(b,zk,96)||new zk;var d=an();d=Object.keys(Pk).indexOf(d);d=-1===d?null:d;null!==d&&F(c,3,d);H(b,zk,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=an())}
function Cp(a,b){var c=B("yt.embedded_player.embed_url");c&&(a?(b=$d(a,Fk,7)||new Fk,F(b,4,c),H(a,Fk,7,b)):b&&(b.thirdParty={embedUrl:c}))}
function Dp(a,b){var c;if(R("web_log_memory_total_kbytes")&&(null==(c=x.navigator)?0:c.deviceMemory)){var d;c=null==(d=x.navigator)?void 0:d.deviceMemory;a?F(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function Ep(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=$d(b,yk,62))?d:new yk;F(c,6,a.appInstallData);H(b,yk,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function Fp(a,b){var c=sn();c&&(a?F(a,61,on[c]):b&&(b.client.connectionType=c));R("web_log_effective_connection_type")&&(c=tn())&&(a?F(a,94,pn[c]):b&&(b.client.effectiveConnectionType=c))}
function Ip(a,b,c){c=void 0===c?{}:c;var d={};O("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":O("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||O("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.authorization||O("AUTHORIZATION");b||(a?b="Bearer "+B("gapi.auth.getToken")().yf:(a=Ym(Xm()),R("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
function Gp(a,b){if(!vp.h){var c=new vp;vp.h=c}c=vp.h;var d=S()-c.h;if(0!==c.h&&d<om("send_config_hash_timer"))c=void 0;else{d=B("yt.gcf.config.coldConfigData");var e=B("yt.gcf.config.hotHashData"),f=B("yt.gcf.config.coldHashData");d&&e&&f&&(c.h=S());c={coldConfigData:d,hotHashData:e,coldHashData:f}}if(e=c)if(c=e.coldConfigData,d=e.coldHashData,e=e.hotHashData,c&&d&&e)if(a){var g;b=null!=(g=$d(a,yk,62))?g:new yk;F(b,1,c);F(b,3,d);F(b,5,e);H(a,yk,62,b)}else b&&(b.client.configInfo=b.client.configInfo||
{},b.client.configInfo.coldConfigData=c,b.client.configInfo.coldHashData=d,b.client.configInfo.hotHashData=e)}
;function Jp(a,b){this.version=a;this.args=b}
Jp.prototype.serialize=function(){return{version:this.version,args:this.args}};function Kp(){this.topic="aft-recorded"}
Kp.prototype.toString=function(){return this.topic};var Lp=B("ytPubsub2Pubsub2Instance")||new Pi;Pi.prototype.subscribe=Pi.prototype.subscribe;Pi.prototype.unsubscribeByKey=Pi.prototype.Eb;Pi.prototype.publish=Pi.prototype.bb;Pi.prototype.clear=Pi.prototype.clear;A("ytPubsub2Pubsub2Instance",Lp);A("ytPubsub2Pubsub2SubscribedKeys",B("ytPubsub2Pubsub2SubscribedKeys")||{});A("ytPubsub2Pubsub2TopicToKeys",B("ytPubsub2Pubsub2TopicToKeys")||{});A("ytPubsub2Pubsub2IsAsync",B("ytPubsub2Pubsub2IsAsync")||{});A("ytPubsub2Pubsub2SkipSubKey",null);
function Mp(a,b){var c=B("ytPubsub2Pubsub2Instance");c&&c.publish.call(c,a.toString(),a,b)}
;function Np(a,b,c){c=void 0===c?{sampleRate:.1}:c;Math.random()<Math.min(.02,c.sampleRate/100)&&Mp("meta_logging_csi_event",{timerName:a,Sf:b})}
;var Op=om("max_body_size_to_compress",5E5),Pp=om("min_body_size_to_compress",500),Qp=!0,Rp=0,Sp=0,Tp=om("compression_performance_threshold",250),Up=om("slow_compressions_before_abandon_count",10);
function Vp(a,b,c,d){var e=S(),f={startTime:e,ticks:{},infos:{}};if(Qp)try{var g=Wp(b);if(null==g||!(g>Op||g<Pp)){var h=sk(ni(b)),l=S();f.ticks.gelc=l;Sp++;R("disable_compression_due_to_performance_degredation")&&l-e>=Tp&&(Rp++,R("abandon_compression_after_N_slow_zips")?Sp===om("compression_disable_point")&&Rp>Up&&(Qp=!1):Qp=!1);Xp(f);c.headers||(c.headers={});c.headers["Content-Encoding"]="gzip";c.postBody=h;c.postParams=void 0}d(a,c)}catch(m){am(m),d(a,c)}else d(a,c)}
function Yp(a){var b=void 0===b?!1:b;var c=S(),d={startTime:c,ticks:{},infos:{}};if(Qp){if(!a.body)return a;try{var e="string"===typeof a.body?a.body:JSON.stringify(a.body),f=Wp(e);if(null!=f&&(f>Op||f<Pp))return a;var g=sk(ni(e)),h=S();d.ticks.gelc=h;if(b){Sp++;if(R("disable_compression_due_to_performance_degredation")&&h-c>=Tp)if(Rp++,R("abandon_compression_after_N_slow_zips")){b=Rp/Sp;var l=Up/om("compression_disable_point");0<Sp&&0===Sp%om("compression_disable_point")&&b>=l&&(Qp=!1)}else Qp=!1;
Xp(d)}a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=g;return a}catch(m){return am(m),a}}else return a}
function Wp(a){try{return(new Blob(a.split(""))).size}catch(b){return am(b),null}}
function Xp(a){R("gel_compression_csi_killswitch")||!R("log_gel_compression_latency")&&!R("log_gel_compression_latency_lr")||Np("gel_compression",a,{sampleRate:.1})}
;function Zp(a){a=Object.assign({},a);delete a.Authorization;var b=Ig();if(b){var c=new yi;c.update(O("INNERTUBE_API_KEY"));c.update(b);a.hash=td(c.digest(),3)}return a}
;var $p;function aq(){$p||($p=new Dn("yt.innertube"));return $p}
function bq(a,b,c,d){if(d)return null;d=aq().get("nextId",!0)||1;var e=aq().get("requests",!0)||{};e[d]={method:a,request:b,authState:Zp(c),requestTime:Math.round(S())};aq().set("nextId",d+1,86400,!0);aq().set("requests",e,86400,!0);return d}
function cq(a){var b=aq().get("requests",!0)||{};delete b[a];aq().set("requests",b,86400,!0)}
function dq(a){var b=aq().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(S())-d.requestTime)){var e=d.authState,f=Zp(Ip(!1));rb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(S())),eq(a,d.method,e,{}));delete b[c]}}aq().set("requests",b,86400,!0)}}
;function fq(a){this.Wb=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.tb=function(){};
this.now=Date.now;this.Ib=!1;var b;this.Gd=null!=(b=a.Gd)?b:100;var c;this.Ad=null!=(c=a.Ad)?c:1;var d;this.yd=null!=(d=a.yd)?d:2592E6;var e;this.wd=null!=(e=a.wd)?e:12E4;var f;this.zd=null!=(f=a.zd)?f:5E3;var g;this.P=null!=(g=a.P)?g:void 0;this.cc=!!a.cc;var h;this.Zb=null!=(h=a.Zb)?h:.1;var l;this.jc=null!=(l=a.jc)?l:10;a.handleError&&(this.handleError=a.handleError);a.tb&&(this.tb=a.tb);a.Ib&&(this.Ib=a.Ib);a.Wb&&(this.Wb=a.Wb);this.R=a.R;this.Aa=a.Aa;this.Y=a.Y;this.X=a.X;this.Ra=a.Ra;this.Kc=
a.Kc;this.Jc=a.Jc;gq(this)&&(!this.R||this.R("networkless_logging"))&&hq(this)}
function hq(a){gq(a)&&!a.Ib&&(a.h=!0,a.cc&&Math.random()<=a.Zb&&a.Y.Xd(a.P),iq(a),a.X.sa()&&a.Ob(),a.X.listen(a.Kc,a.Ob.bind(a)),a.X.listen(a.Jc,a.Yc.bind(a)))}
k=fq.prototype;k.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(gq(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.Y.set(d,this.P).then(function(e){d.id=e;c.X.sa()&&jq(c,d)}).catch(function(e){jq(c,d);
kq(c,e)})}else this.Ra(a,b)};
k.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(gq(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.R&&this.R("nwl_skip_retry")&&(e.skipRetry=c);if(this.X.sa()||this.R&&this.R("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return w(function(l){if(1==l.h)return l.yield(d.Y.set(e,d.P).catch(function(m){kq(d,m)}),2);
f(g,h);l.h=0})}}this.Ra(a,b,e.skipRetry)}else this.Y.set(e,this.P).catch(function(g){d.Ra(a,b,e.skipRetry);
kq(d,g)})}else this.Ra(a,b,this.R&&this.R("nwl_skip_retry")&&c)};
k.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(gq(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.Y.sb(d.id,c.P):e=!0;c.X.fb&&c.R&&c.R("vss_network_hint")&&c.X.fb(!0);f(g,h)};
this.Ra(d.url,d.options);this.Y.set(d,this.P).then(function(g){d.id=g;e&&c.Y.sb(d.id,c.P)}).catch(function(g){kq(c,g)})}else this.Ra(a,b)};
k.Ob=function(){var a=this;if(!gq(this))throw eo("throttleSend");this.i||(this.i=this.Aa.ma(function(){var b;return w(function(c){if(1==c.h)return c.yield(a.Y.hd("NEW",a.P),2);if(3!=c.h)return b=c.i,b?c.yield(jq(a,b),3):(a.Yc(),c.return());a.i&&(a.i=0,a.Ob());c.h=0})},this.Gd))};
k.Yc=function(){this.Aa.Fa(this.i);this.i=0};
function jq(a,b){var c,d;return w(function(e){switch(e.h){case 1:if(!gq(a))throw c=eo("immediateSend"),c;if(void 0===b.id){e.A(2);break}return e.yield(a.Y.te(b.id,a.P),3);case 3:(d=e.i)||a.tb(Error("The request cannot be found in the database."));case 2:if(lq(a,b,a.yd)){e.A(4);break}a.tb(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.A(5);break}return e.yield(a.Y.sb(b.id,a.P),5);case 5:return e.return();case 4:b.skipRetry||(b=mq(a,b));if(!b){e.A(0);break}if(!b.skipRetry||
void 0===b.id){e.A(8);break}return e.yield(a.Y.sb(b.id,a.P),8);case 8:a.Ra(b.url,b.options,!!b.skipRetry),e.h=0}})}
function mq(a,b){if(!gq(a))throw eo("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,l,m;return w(function(p){switch(p.h){case 1:g=nq(f);(h=oq(f))&&a.R&&a.R("web_enable_error_204")&&a.handleError(Error("Request failed due to compression"),b.url,f);if(!(a.R&&a.R("nwl_consider_error_code")&&g||a.R&&!a.R("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.jc)){p.A(2);break}if(!a.X.mc){p.A(3);break}return p.yield(a.X.mc(),3);case 3:if(a.X.sa()){p.A(2);break}c(e,f);if(!a.R||!a.R("nwl_consider_error_code")||void 0===(null==(l=b)?void 0:l.id)){p.A(6);
break}return p.yield(a.Y.Nc(b.id,a.P,!1),6);case 6:return p.return();case 2:if(a.R&&a.R("nwl_consider_error_code")&&!g&&a.potentialEsfErrorCounter>a.jc)return p.return();a.potentialEsfErrorCounter++;if(void 0===(null==(m=b)?void 0:m.id)){p.A(8);break}return b.sendCount<a.Ad?p.yield(a.Y.Nc(b.id,a.P,!0,h?!1:void 0),12):p.yield(a.Y.sb(b.id,a.P),8);case 12:a.Aa.ma(function(){a.X.sa()&&a.Ob()},a.zd);
case 8:c(e,f),p.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return w(function(h){if(1==h.h)return void 0===(null==(g=b)?void 0:g.id)?h.A(2):h.yield(a.Y.sb(b.id,a.P),2);a.X.fb&&a.R&&a.R("vss_network_hint")&&a.X.fb(!0);d(e,f);h.h=0})};
return b}
function lq(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function iq(a){if(!gq(a))throw eo("retryQueuedRequests");a.Y.hd("QUEUED",a.P).then(function(b){b&&!lq(a,b,a.wd)?a.Aa.ma(function(){return w(function(c){if(1==c.h)return void 0===b.id?c.A(2):c.yield(a.Y.Nc(b.id,a.P),2);iq(a);c.h=0})}):a.X.sa()&&a.Ob()})}
function kq(a,b){a.Md&&!a.X.sa()?a.Md(b):a.handleError(b)}
function gq(a){return!!a.P||a.Wb}
function nq(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
function oq(a){var b;a=null==a?void 0:null==(b=a.error)?void 0:b.code;return!(400!==a&&415!==a)}
;var pq;
function qq(){if(pq)return pq();var a={};pq=mp("LogsDatabaseV2",{zb:(a.LogsRequestsStore={Gb:2},a),nc:!1,upgrade:function(b,c,d){c(2)&&to(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),Ao(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return pq()}
;function rq(a){return Mo(qq(),a)}
function sq(a,b){var c,d,e,f;return w(function(g){if(1==g.h)return c={startTime:S(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},ticks:{}},g.yield(rq(b),2);if(3!=g.h)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:O("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),g.yield(vo(d,"LogsRequestsStore",e),3);f=g.i;c.ticks.tc=S();tq(c);return g.return(f)})}
function uq(a,b){var c,d,e,f,g,h,l;return w(function(m){if(1==m.h)return c={startTime:S(),infos:{transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},ticks:{}},m.yield(rq(b),2);if(3!=m.h)return d=m.i,e=O("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,S()],h=IDBKeyRange.bound(f,g),l=void 0,m.yield(so(d,["LogsRequestsStore"],{mode:"readwrite",fa:!0},function(p){return Fo(p.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(r){r.getValue()&&(l=r.getValue(),"NEW"===
a&&(l.status="QUEUED",r.update(l)))})}),3);
c.ticks.tc=S();tq(c);return m.return(l)})}
function vq(a,b){var c;return w(function(d){if(1==d.h)return d.yield(rq(b),2);c=d.i;return d.return(so(c,["LogsRequestsStore"],{mode:"readwrite",fa:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",oo(f.h.put(g,void 0)).then(function(){return g})})}))})}
function wq(a,b,c,d){c=void 0===c?!0:c;var e;return w(function(f){if(1==f.h)return f.yield(rq(b),2);e=f.i;return f.return(so(e,["LogsRequestsStore"],{mode:"readwrite",fa:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(l){return l?(l.status="NEW",c&&(l.sendCount+=1),void 0!==d&&(l.options.compress=d),oo(h.h.put(l,void 0)).then(function(){return l})):io.resolve(void 0)})}))})}
function xq(a,b){var c;return w(function(d){if(1==d.h)return d.yield(rq(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function yq(a){var b,c;return w(function(d){if(1==d.h)return d.yield(rq(a),2);b=d.i;c=S()-2592E6;return d.yield(so(b,["LogsRequestsStore"],{mode:"readwrite",fa:!0},function(e){return Co(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function zq(){w(function(a){return a.yield(ip(),0)})}
function tq(a){R("nwl_csi_killswitch")||Np("networkless_performance",a,{sampleRate:1})}
;var Aq={},Bq=mp("ServiceWorkerLogsDatabase",{zb:(Aq.SWHealthLog={Gb:1},Aq),nc:!0,upgrade:function(a,b){b(1)&&Ao(to(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function Cq(a){return Mo(Bq(),a)}
function Dq(a){var b,c;w(function(d){if(1==d.h)return d.yield(Cq(a),2);b=d.i;c=S()-2592E6;return d.yield(so(b,["SWHealthLog"],{mode:"readwrite",fa:!0},function(e){return Co(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Eq(a){var b;return w(function(c){if(1==c.h)return c.yield(Cq(a),2);b=c.i;return c.yield(b.clear("SWHealthLog"),0)})}
;var Fq={},Gq=0;function Hq(a){var b=new Image,c=""+Gq++;Fq[c]=b;b.onload=b.onerror=function(){delete Fq[c]};
b.src=a}
;function Iq(){this.h=new Map;this.i=!1}
function Jq(){if(!Iq.h){var a=B("yt.networkRequestMonitor.instance")||new Iq;A("yt.networkRequestMonitor.instance",a);Iq.h=a}return Iq.h}
Iq.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Iq.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:!1===a&&this.i?!0:null};
Iq.prototype.removeParams=function(a){return a.split("?")[0]};
Iq.prototype.removeParams=Iq.prototype.removeParams;Iq.prototype.isEndpointCFR=Iq.prototype.isEndpointCFR;Iq.prototype.requestComplete=Iq.prototype.requestComplete;Iq.getInstance=Jq;var Kq;function Lq(){Kq||(Kq=new Dn("yt.offline"));return Kq}
function Mq(a){if(R("offline_error_handling")){var b=Lq().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Lq().set("errors",b,2592E3,!0)}}
;function Nq(){ef.call(this);var a=this;this.j=!1;this.i=ri();this.i.listen("networkstatus-online",function(){if(a.j&&R("offline_error_handling")){var b=Lq().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new un(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;$l(d)}Lq().set("errors",{},2592E3,!0)}}})}
v(Nq,ef);function Oq(){if(!Nq.h){var a=B("yt.networkStatusManager.instance")||new Nq;A("yt.networkStatusManager.instance",a);Nq.h=a}return Nq.h}
k=Nq.prototype;k.sa=function(){return this.i.sa()};
k.fb=function(a){this.i.i=a};
k.le=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
k.be=function(){this.j=!0};
k.listen=function(a,b){return this.i.listen(a,b)};
k.mc=function(a){a=pi(this.i,a);a.then(function(b){R("use_cfr_monitor")&&Jq().requestComplete("generate_204",b)});
return a};
Nq.prototype.sendNetworkCheckRequest=Nq.prototype.mc;Nq.prototype.listen=Nq.prototype.listen;Nq.prototype.enableErrorFlushing=Nq.prototype.be;Nq.prototype.getWindowStatus=Nq.prototype.le;Nq.prototype.networkStatusHint=Nq.prototype.fb;Nq.prototype.isNetworkAvailable=Nq.prototype.sa;Nq.getInstance=Oq;function Pq(a){a=void 0===a?{}:a;ef.call(this);var b=this;this.i=this.s=0;this.j=Oq();var c=B("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.lc?(this.lc=a.lc,c("networkstatus-online",function(){Qq(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Qq(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){ff(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){ff(b,"publicytnetworkstatus-offline")})))}
v(Pq,ef);Pq.prototype.sa=function(){var a=B("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
Pq.prototype.fb=function(a){var b=B("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
Pq.prototype.mc=function(a){var b=this,c;return w(function(d){c=B("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return R("skip_network_check_if_cfr")&&Jq().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.fb((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.sa())})):c?d.return(c(a)):d.return(!0)})};
function Qq(a,b){a.lc?a.i?(si.Fa(a.s),a.s=si.ma(function(){a.m!==b&&(ff(a,b),a.m=b,a.i=S())},a.lc-(S()-a.i))):(ff(a,b),a.m=b,a.i=S()):ff(a,b)}
;var Rq;function Sq(){var a=fq.call;Rq||(Rq=new Pq({Hf:!0,Cf:!0}));a.call(fq,this,{Y:{Xd:yq,sb:xq,hd:uq,te:vq,Nc:wq,set:sq},X:Rq,handleError:function(b,c,d){var e,f=null==d?void 0:null==(e=d.error)?void 0:e.code;if(400===f||415===f){var g;am(new un(b.message,c,null==d?void 0:null==(g=d.error)?void 0:g.code),void 0,void 0,void 0,!0)}else $l(b)},
tb:am,Ra:Tq,now:S,Md:Mq,Aa:Cn(),Kc:"publicytnetworkstatus-online",Jc:"publicytnetworkstatus-offline",cc:!0,Zb:.1,jc:om("potential_esf_error_limit",10),R:R,Ib:!(vn()&&Uq())});this.j=new Nh;R("networkless_immediately_drop_all_requests")&&zq();jp("LogsDatabaseV2")}
v(Sq,fq);function br(){var a=B("yt.networklessRequestController.instance");a||(a=new Sq,A("yt.networklessRequestController.instance",a),R("networkless_logging")&&Zo().then(function(b){a.P=b;hq(a);a.j.resolve();a.cc&&Math.random()<=a.Zb&&a.P&&Dq(a.P);R("networkless_immediately_drop_sw_health_store")&&fr(a)}));
return a}
Sq.prototype.writeThenSend=function(a,b){b||(b={});vn()||(this.h=!1);fq.prototype.writeThenSend.call(this,a,b)};
Sq.prototype.sendThenWrite=function(a,b,c){b||(b={});vn()||(this.h=!1);fq.prototype.sendThenWrite.call(this,a,b,c)};
Sq.prototype.sendAndWrite=function(a,b){b||(b={});vn()||(this.h=!1);fq.prototype.sendAndWrite.call(this,a,b)};
Sq.prototype.awaitInitialization=function(){return this.j.promise};
function fr(a){var b;w(function(c){if(!a.P)throw b=eo("clearSWHealthLogsDb"),b;return c.return(Eq(a.P).catch(function(d){a.handleError(d)}))})}
function Tq(a,b,c){b=R("web_fp_via_jspb")?Object.assign({},b):b;R("use_cfr_monitor")&&Ar(a,b);if(R("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(S())));else{var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(S())}if(c&&0===Object.keys(b).length){var e=void 0===e?"":e;var f=void 0===f?!1:f;if(a)if(e)Em(a,void 0,"POST",e);else if(O("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))Em(a,void 0,"GET","",void 0,void 0,f);else{b:{try{var g=
new cb({url:a});if(g.j&&g.i||g.l){var h=vc(wc(5,a)),l;if(!(l=!h||!h.endsWith("/aclk"))){var m=a.search(Hc),p=Gc(a,0,"ri",m);if(0>p)var r=null;else{var y=a.indexOf("&",p);if(0>y||y>m)y=m;r=decodeURIComponent(a.slice(p+3,-1!==y?y:0).replace(/\+/g," "))}l="1"!==r}var u=!l;break b}}catch(D){}u=!1}if(u){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var z=!0;break b}}catch(D){}z=!1}c=z?!0:!1}else c=!1;c||Hq(a)}}else b.compress?b.postBody?("string"!==typeof b.postBody&&
(b.postBody=JSON.stringify(b.postBody)),Vp(a,b.postBody,b,Bm)):Vp(a,JSON.stringify(b.postParams),b,Jm):Bm(a,b)}
function Ar(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Jq().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Jq().requestComplete(a,!0);d(e,f)}}
function Uq(){return"www.youtube-nocookie.com"!==xc(document.location.toString())}
;var Br=!1,Cr=x.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Br};A("ytNetworklessLoggingInitializationOptions",Cr);function Dr(){var a;w(function(b){if(1==b.h)return b.yield(Zo(),2);a=b.i;if(!a||!vn()&&!R("nwl_init_require_datasync_id_killswitch")||!Uq())return b.A(0);Br=!0;Cr.isNwlInitialized=Br;return b.yield(br().awaitInitialization(),0)})}
;function Er(a){var b=this;this.config_=null;a?this.config_=a:yp()&&(this.config_=zp());yn(function(){dq(b)},5E3)}
Er.prototype.isReady=function(){!this.config_&&yp()&&(this.config_=zp());return!!this.config_};
function eq(a,b,c,d){function e(z){z=void 0===z?!1:z;var D;if(d.retry&&"www.youtube-nocookie.com"!=h&&(z||R("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(D=bq(b,c,m,l)),D)){var G=g.onSuccess,M=g.onFetchSuccess;g.onSuccess=function(T,da){cq(D);G(T,da)};
c.onFetchSuccess=function(T,da){cq(D);M(T,da)}}try{if(z&&d.retry&&!d.rd.bypassNetworkless)g.method="POST",d.rd.writeThenSend?br().writeThenSend(u,g):br().sendAndWrite(u,g);
else if(d.compress)if(g.postBody){var P=g.postBody;"string"!==typeof P&&(P=JSON.stringify(g.postBody));Vp(u,P,g,Bm)}else Vp(u,JSON.stringify(g.postParams),g,Jm);else R("web_all_payloads_via_jspb")?Bm(u,g):Jm(u,g)}catch(T){if("InvalidAccessError"==T.name)D&&(cq(D),D=0),am(Error("An extension is blocking network request."));else throw T;}D&&yn(function(){dq(a)},5E3)}
!O("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&am(new un("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new un("innertube xhrclient not ready",b,c,d);$l(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(z,D){if(d.onSuccess)d.onSuccess(D)},
onFetchSuccess:function(z){if(d.onSuccess)d.onSuccess(z)},
onError:function(z,D){if(d.onError)d.onError(D)},
onFetchError:function(z){if(d.onError)d.onError(z)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.pe)&&(h=f);var l=a.config_.re||!1,m=Ip(l,h,d);Object.assign(g.headers,m);(f=g.headers.Authorization)&&!h&&l&&(g.headers["x-origin"]=window.location.origin);var p="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,r={alt:"json"},y=a.config_.qe&&f;y=y&&f.startsWith("Bearer");y||(r.key=a.config_.innertubeApiKey);var u=jm(""+h+p,r||{},!0);(B("ytNetworklessLoggingInitializationOptions")?
Cr.isNwlInitialized:Br)?Xo().then(function(z){e(z)}):e(!1)}
;var Fr=0,Gr=cd?"webkit":bd?"moz":$c?"ms":Zc?"o":"";A("ytDomDomGetNextId",B("ytDomDomGetNextId")||function(){return++Fr});var Hr={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Ir(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Hr||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function Jr(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
Ir.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Ir.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Ir.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var ob=x.ytEventsEventsListeners||{};A("ytEventsEventsListeners",ob);var Kr=x.ytEventsEventsCounter||{count:0};A("ytEventsEventsCounter",Kr);
function Lr(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return nb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Sa(e[4])&&Sa(d)&&rb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Mr=eb(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Nr(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Lr(a,b,c,d);if(e)return e;e=++Kr.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Ir(h);if(!uf(h.relatedTarget,function(l){return l==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Ir(h);
h.currentTarget=a;return c.call(a,h)};
g=Zl(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Mr()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);ob[e]=[a,b,c,g,d];return e}
function Or(a){a&&("string"==typeof a&&(a=[a]),gb(a,function(b){if(b in ob){var c=ob[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Mr()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete ob[b]}}))}
;function Pr(a){this.M=a;this.i=null;this.m=0;this.v=null;this.s=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.W=Nr(window,"mousemove",Ya(this.Z,this));a=Ya(this.T,this);"function"===typeof a&&(a=Zl(a));this.aa=window.setInterval(a,25)}
$a(Pr,J);Pr.prototype.Z=function(a){void 0===a.h&&Jr(a);var b=a.h;void 0===a.i&&Jr(a);this.i=new qf(b,a.i)};
Pr.prototype.T=function(){if(this.i){var a=S();if(0!=this.m){var b=this.v,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.s)/this.s)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.M();this.s=d}this.m=a;this.v=this.i;this.l=(this.l+1)%4}};
Pr.prototype.K=function(){window.clearInterval(this.aa);Or(this.W)};var Qr=new Set([174,173,175]),Rr={};
function Sr(a){var b=void 0===a?{}:a;a=void 0===b.Be?!1:b.Be;b=void 0===b.ce?!0:b.ce;if(null==B("_lact",window)){var c=parseInt(O("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;A("_lact",c,window);A("_fact",c,window);-1==c&&Tr();Nr(document,"keydown",Tr);Nr(document,"keyup",Tr);Nr(document,"mousedown",Tr);Nr(document,"mouseup",Tr);a?Nr(window,"touchmove",function(){Ur("touchmove",200)},{passive:!0}):(Nr(window,"resize",function(){Ur("resize",200)}),b&&Nr(window,"scroll",function(){Ur("scroll",
200)}));
new Pr(function(){Ur("mouse",100)});
Nr(document,"touchstart",Tr,{passive:!0});Nr(document,"touchend",Tr,{passive:!0})}}
function Ur(a,b){Rr[a]||(Rr[a]=!0,si.ma(function(){Tr();Rr[a]=!1},b))}
function Tr(a){var b;if(null!=(b=B("experiment.flags",window))&&b.enable_lact_reset_by_volume_buttons||!Qr.has(null==a?void 0:a.keyCode))null==B("_lact",window)&&Sr(),a=Date.now(),A("_lact",a,window),-1==B("_fact",window)&&A("_fact",a,window),(a=B("ytglobal.ytUtilActivityCallback_"))&&a()}
function Vr(){var a=B("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var Wr=x.ytPubsubPubsubInstance||new Pi,Xr=x.ytPubsubPubsubSubscribedKeys||{},Yr=x.ytPubsubPubsubTopicToKeys||{},Zr=x.ytPubsubPubsubIsSynchronous||{};function $r(a,b){var c=as();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){Xr[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{Zr[a]?f():um(f,0)}catch(g){$l(g)}},void 0);
Xr[d]=!0;Yr[a]||(Yr[a]=[]);Yr[a].push(d);return d}return 0}
function bs(a){var b=as();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),gb(a,function(c){b.unsubscribeByKey(c);delete Xr[c]}))}
function cs(a,b){var c=as();c&&c.publish.apply(c,arguments)}
function ds(a){var b=as();if(b)if(b.clear(a),a)es(a);else for(var c in Yr)es(c)}
function as(){return x.ytPubsubPubsubInstance}
function es(a){Yr[a]&&(a=Yr[a],gb(a,function(b){Xr[b]&&delete Xr[b]}),a.length=0)}
Pi.prototype.subscribe=Pi.prototype.subscribe;Pi.prototype.unsubscribeByKey=Pi.prototype.Eb;Pi.prototype.publish=Pi.prototype.bb;Pi.prototype.clear=Pi.prototype.clear;A("ytPubsubPubsubInstance",Wr);A("ytPubsubPubsubTopicToKeys",Yr);A("ytPubsubPubsubIsSynchronous",Zr);A("ytPubsubPubsubSubscribedKeys",Xr);var gs=Symbol("injectionDeps");function hs(a){this.name=a}
hs.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function is(a){this.key=a}
function js(){this.h=new Map;this.i=new Map}
js.prototype.resolve=function(a){return a instanceof is?ks(this,a.key,[],!0):ks(this,a,[])};
function ks(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.h.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.h.get(b);c.push(b);if(void 0!==d.Jd)var e=d.Jd;else if(d.af)e=d[gs]?ls(a,d[gs],c):[],e=d.af.apply(d,ia(e));else if(d.Id){e=d.Id;var f=e[gs]?ls(a,e[gs],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ia(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Qf||a.i.set(b,e);return e}
function ls(a,b,c){return b?b.map(function(d){return d instanceof is?ks(a,d.key,c,!0):ks(a,d,c)}):[]}
;var ms;function ns(){ms||(ms=new js);return ms}
;function ps(){this.store={};this.h={}}
ps.prototype.storePayload=function(a,b){a=qs(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);return a};
ps.prototype.smartExtractMatchingEntries=function(a){if(!a.keys.length)return[];for(var b=rs(this,a.keys.splice(0,1)[0]),c=[],d=0;d<b.length;d++)this.store[b[d]]&&a.sizeLimit&&(this.store[b[d]].length<=a.sizeLimit?(c.push.apply(c,ia(this.store[b[d]])),delete this.store[b[d]]):c.push.apply(c,ia(this.store[b[d]].splice(0,a.sizeLimit))));(null==a?0:a.sizeLimit)&&c.length<(null==a?void 0:a.sizeLimit)&&(a.sizeLimit-=c.length,c.push.apply(c,ia(this.smartExtractMatchingEntries(a))));return c};
ps.prototype.extractMatchingEntries=function(a){a=rs(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,ia(this.store[a[c]])),delete this.store[a[c]]);return b};
ps.prototype.getSequenceCount=function(a){a=rs(this,a);for(var b=0,c=0;c<a.length;c++){var d=void 0;b+=(null==(d=this.store[a[c]])?void 0:d.length)||0}return b};
function rs(a,b){var c=qs(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(1>=d.length&&qs(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(ss(b.auth,g[0])){var h=b.isJspb;ss(void 0===h?"undefined":h?"true":"false",g[1])&&ss(b.cttAuthInfo,g[2])&&(h=b.tier,h=void 0===h?"undefined":JSON.stringify(h),ss(h,g[3])&&e.push(d[f]))}}return a.h[c]=e}
function ss(a,b){return void 0===a||"undefined"===a?!0:a===b}
ps.prototype.getSequenceCount=ps.prototype.getSequenceCount;ps.prototype.extractMatchingEntries=ps.prototype.extractMatchingEntries;ps.prototype.smartExtractMatchingEntries=ps.prototype.smartExtractMatchingEntries;ps.prototype.storePayload=ps.prototype.storePayload;function qs(a){return[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo,void 0===a.tier?"undefined":a.tier].join("/")}
;function ts(a,b){if(a)return a[b.name]}
;var us=om("initial_gel_batch_timeout",2E3),vs=om("gel_queue_timeout_max_ms",6E4),ws=Math.pow(2,16)-1,xs=void 0;function ys(){this.j=this.h=this.i=0}
var zs=new ys,As=new ys,Bs=new ys,Cs=new ys,Ds,Es=!0,Fs=x.ytLoggingTransportTokensToCttTargetIds_||{};A("ytLoggingTransportTokensToCttTargetIds_",Fs);var Gs=x.ytLoggingTransportTokensToJspbCttTargetIds_||{};A("ytLoggingTransportTokensToJspbCttTargetIds_",Gs);var Hs={};function Is(){var a=B("yt.logging.ims");a||(a=new ps,A("yt.logging.ims",a));return a}
function Js(a,b){if("log_event"===a.endpoint){Ks(a);var c=Ls(a),d=R("enable_web_tiered_gel")?200:void 0;Hs[c]=!0;d={cttAuthInfo:c,isJspb:!1,tier:d};Is().storePayload(d,a.payload);Ms(b,c,!1,d)}}
function Ns(a,b){if("log_event"===a.endpoint){Ks(void 0,a);var c=Ls(a,!0),d=R("enable_web_tiered_gel")?200:void 0;Hs[c]=!0;d={cttAuthInfo:c,isJspb:!0,tier:d};Is().storePayload(d,a.payload.toJSON());Ms(b,c,!0,d)}}
function Ms(a,b,c,d){c=void 0===c?!1:c;a&&(xs=new a);a=Os();var e=S(),f=Ps(c,d.tier),g=f.j,h=0;d&&(h=Is().getSequenceCount(d));h>=a?Ds||(Ds=Qs(function(){Rs({writeThenSend:!0},R("flush_only_full_queue")?b:void 0,c,d.tier);Ds=void 0},0)):10<=e-g&&(Ss(c,d.tier),f.j=e)}
function Ts(a,b){if("log_event"===a.endpoint){Ks(a);var c=Ls(a),d=new Map;d.set(c,[a.payload]);b&&(xs=new b);return new Gf(function(e,f){xs&&xs.isReady()?Us(d,xs,e,f,{bypassNetworkless:!0},!0):e()})}}
function Vs(a,b){if("log_event"===a.endpoint){Ks(void 0,a);var c=Ls(a,!0),d=new Map;d.set(c,[a.payload.toJSON()]);b&&(xs=new b);return new Gf(function(e){xs&&xs.isReady()?Ws(d,xs,e,{bypassNetworkless:!0},!0):e()})}}
function Ls(a,b){var c="";if(a.dangerousLogToVisitorSession)c="visitorOnlyApprovedKey";else if(a.cttAuthInfo){if(void 0===b?0:b){b=a.cttAuthInfo.token;c=a.cttAuthInfo;var d=new Fl;c.videoId?d.setVideoId(c.videoId):c.playlistId&&Yd(d,2,Gl,c.playlistId);Gs[b]=d}else b=a.cttAuthInfo,c={},b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId),Fs[a.cttAuthInfo.token]=c;c=a.cttAuthInfo.token}return c}
function Rs(a,b,c,d){a=void 0===a?{}:a;c=void 0===c?!1:c;new Gf(function(e,f){var g=Ps(c,d);Xs(g.i);Xs(g.h);g.h=0;xs&&xs.isReady()?void 0===d&&R("enable_web_tiered_gel")?(Ys(e,f,a,b,c,300),Ys(e,f,a,b,c,200)):Ys(e,f,a,b,c,d):(Ss(c,d),e())})}
function Ys(a,b,c,d,e,f){var g=xs;c=void 0===c?{}:c;e=void 0===e?!1:e;f=void 0===f?200:f;var h=new Map,l=new Map,m={isJspb:e,cttAuthInfo:d,tier:f},p={isJspb:e,cttAuthInfo:d};if(void 0!==d)e?(b=R("enable_web_tiered_gel")?Is().smartExtractMatchingEntries({keys:[m,p],sizeLimit:Os()}):Is().extractMatchingEntries(p),h.set(d,b),Ws(h,g,a,c)):(h=R("enable_web_tiered_gel")?Is().smartExtractMatchingEntries({keys:[m,p],sizeLimit:Os()}):Is().extractMatchingEntries(p),l.set(d,h),Us(l,g,a,b,c));else if(e){b=t(Object.keys(Hs));
for(d=b.next();!d.done;d=b.next())l=d.value,f=R("enable_web_tiered_gel")?Is().smartExtractMatchingEntries({keys:[m,p],sizeLimit:Os()}):Is().extractMatchingEntries({isJspb:!0,cttAuthInfo:l}),0<f.length&&h.set(l,f),delete Hs[l];Ws(h,g,a,c)}else{h=t(Object.keys(Hs));for(d=h.next();!d.done;d=h.next())m=d.value,p=R("enable_web_tiered_gel")?Is().smartExtractMatchingEntries({keys:[{isJspb:!1,cttAuthInfo:m,tier:f},{isJspb:!1,cttAuthInfo:m}],sizeLimit:Os()}):Is().extractMatchingEntries({isJspb:!1,cttAuthInfo:m}),
0<p.length&&l.set(m,p),delete Hs[m];Us(l,g,a,b,c)}}
function Ss(a,b){a=void 0===a?!1:a;b=void 0===b?200:b;var c=Ps(a,b),d=c===Cs||c===Bs?5E3:vs;R("web_gel_timeout_cap")&&!c.h&&(d=Qs(function(){Rs({writeThenSend:!0},void 0,a,b)},d),c.h=d);
Xs(c.i);d=O("LOGGING_BATCH_TIMEOUT",om("web_gel_debounce_ms",1E4));R("shorten_initial_gel_batch_timeout")&&Es&&(d=us);d=Qs(function(){Rs({writeThenSend:!0},void 0,a,b)},d);
c.i=d}
function Us(a,b,c,d,e,f){e=void 0===e?{}:e;var g=Math.round(S()),h=a.size,l={};a=t(a);for(var m=a.next();!m.done;l={Pb:l.Pb,Ya:l.Ya,Cb:l.Cb,Rb:l.Rb,Qb:l.Qb},m=a.next()){var p=t(m.value);m=p.next().value;p=p.next().value;l.Ya=tb({context:Ap(b.config_||zp())});if(!Ra(p)&&!R("throw_err_when_logevent_malformed_killswitch")){d();break}l.Ya.events=p;(p=Fs[m])&&Zs(l.Ya,m,p);delete Fs[m];l.Cb="visitorOnlyApprovedKey"===m;$s(l.Ya,g,l.Cb);at(e);l.Rb=function(r){R("update_log_event_config")&&si.ma(function(){return w(function(y){return y.yield(bt(r),
0)})});
h--;h||c()};
l.Pb=0;l.Qb=function(r){return function(){r.Pb++;if(e.bypassNetworkless&&1===r.Pb)try{eq(b,"log_event",r.Ya,ct({writeThenSend:!0},r.Cb,r.Rb,r.Qb,f)),Es=!1}catch(y){$l(y),d()}h--;h||c()}}(l);
try{eq(b,"log_event",l.Ya,ct(e,l.Cb,l.Rb,l.Qb,f)),Es=!1}catch(r){$l(r),d()}}}
function Ws(a,b,c,d,e){d=void 0===d?{}:d;var f=Math.round(S()),g=a.size,h=new Map([].concat(ia(a)));h=t(h);for(var l=h.next();!l.done;l=h.next()){var m=t(l.value).next().value,p=a.get(m);l=new Hl;var r=Hp(b.config_||zp());H(l,Ik,1,r);p=p?dt(p):[];p=t(p);for(r=p.next();!r.done;r=p.next())ee(l,3,Cl,r.value);(p=Gs[m])&&et(l,m,p);delete Gs[m];m="visitorOnlyApprovedKey"===m;ft(l,f,m);at(d);p={startTime:S(),ticks:{},infos:{}};l=l.serialize();p.ticks.geljspc=S();R("log_jspb_serialize_latency")&&Np("gel_jspb_serialize",
p,{sampleRate:.1});m=ct(d,m,function(y){R("update_log_event_config")&&si.ma(function(){return w(function(u){return u.yield(bt(y),0)})});
g--;g||c()},function(){g--;
g||c()},e);
m.headers["Content-Type"]="application/json+protobuf";m.postBodyFormat="JSPB";m.postBody=l;eq(b,"log_event","",m);Es=!1}}
function at(a){R("always_send_and_write")&&(a.writeThenSend=!1)}
function ct(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,rd:a,dangerousLogToVisitorSession:b,zf:!!e,headers:{},postBodyFormat:"",postBody:"",compress:R("compress_gel")||R("compress_gel_lr")};gt()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(S())));return a}
function $s(a,b,c){gt()||(a.requestTimeMs=String(b));R("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=O("EVENT_ID"))&&(c=ht(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function ft(a,b,c){gt()||F(a,2,b);if(!c&&(b=O("EVENT_ID"))){c=ht();var d=new El;F(d,1,b);F(d,2,c);H(a,El,5,d)}}
function ht(){var a=O("BATCH_CLIENT_COUNTER")||0;a||(a=Math.floor(Math.random()*ws/2));a++;a>ws&&(a=1);Vl("BATCH_CLIENT_COUNTER",a);return a}
function Zs(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function et(a,b,c){var d=1===Zd(c,Gl)?1:-1;if(Od(c,d))d=1;else if(c.getPlaylistId())d=2;else return;H(a,Fl,4,c);a=$d(a,Ik,1)||new Ik;c=$d(a,Hk,3)||new Hk;var e=new Gk;F(e,2,b);F(e,1,d);ee(c,12,Gk,e);H(a,Hk,3,c)}
function dt(a){for(var b=[],c=0;c<a.length;c++)try{b.push(new Cl(a[c]))}catch(d){$l(new un("Transport failed to deserialize "+String(a[c])))}return b}
function Ks(a,b){if(B("yt.logging.transport.enableScrapingForTest")){var c=B("yt.logging.transport.scrapedPayloadsForTesting"),d=B("yt.logging.transport.payloadToScrape");b&&(b=B("yt.logging.transport.getScrapedPayloadFromClientEventsFunction").bind(b.payload)())&&c.push(b);if(d&&1<=d.length)for(b=0;b<d.length;b++)if(a&&a.payload[d[b]]){var e=void 0;c.push((null==(e=a)?void 0:e.payload)[d[b]])}A("yt.logging.transport.scrapedPayloadsForTesting",c)}}
function gt(){return R("use_request_time_ms_header")||R("lr_use_request_time_ms_header")}
function Qs(a,b){return R("transport_use_scheduler")?yn(a,b):um(a,b)}
function Xs(a){R("transport_use_scheduler")?si.Fa(a):window.clearTimeout(a)}
function bt(a){var b,c,d,e,f,g,h,l,m,p;return w(function(r){return 1==r.h?(d=null==(b=a)?void 0:null==(c=b.responseContext)?void 0:c.globalConfigGroup,e=ts(d,wk),g=null==(f=d)?void 0:f.hotHashData,h=ts(d,vk),m=null==(l=d)?void 0:l.coldHashData,(p=ns().resolve(new is(vp)))?g?e?r.yield(wp(p,g,e),2):r.yield(wp(p,g),2):r.A(2):r.return()):m?h?r.yield(xp(p,m,h),0):r.yield(xp(p,m),0):r.A(0)})}
function Ps(a,b){b=void 0===b?200:b;return a?300===b?Cs:As:300===b?Bs:zs}
function Os(){return om("tvhtml5_logging_max_batch_ads_fork")||om("web_logging_max_batch")||100}
;var jt=x.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",jt);
function kt(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||S());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;R("enable_unknown_lact_fix_on_html5")&&Sr();a=Vr();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};R("log_sequence_info_on_gel_web")&&d.sequenceGroup&&(a=e.context,b=d.sequenceGroup,b={index:lt(b),groupKey:b},a.sequence=b,d.endOfSequence&&delete jt[d.sequenceGroup]);(d.sendIsolatedPayload?Ts:Js)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,
dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},c)}
function mt(a){Rs(void 0,void 0,void 0===a?!1:a)}
function lt(a){jt[a]=a in jt?jt[a]+1:0;return jt[a]}
;var nt=[];function Mn(a,b,c){c=void 0===c?{}:c;var d=Er;O("ytLoggingEventsDefaultDisabled",!1)&&Er===Er&&(d=null);R("web_all_payloads_via_jspb")?(c.timestamp||(c.timestamp=S()),nt.push({payloadName:a,payload:b,options:c})):kt(a,b,d,c)}
;var ot=x.ytLoggingGelSequenceIdObj_||{};A("ytLoggingGelSequenceIdObj_",ot);function pt(a,b){b=void 0===b?{}:b;var c=!1;O("ytLoggingEventsDefaultDisabled",!1)&&(c=!0);c=c?null:Er;b=void 0===b?{}:b;var d=Math.round(b.timestamp||S());F(a,1,d<Number.MAX_SAFE_INTEGER?d:0);var e=Vr();d=new Bl;F(d,1,b.timestamp||!isFinite(e)?-1:e);if(R("log_sequence_info_on_gel_web")&&b.sequenceGroup){e=b.sequenceGroup;var f=lt(e),g=new Al;F(g,2,f);F(g,1,e);H(d,Al,3,g);b.endOfSequence&&delete ot[b.sequenceGroup]}H(a,Bl,33,d);(b.sendIsolatedPayload?Vs:Ns)({endpoint:"log_event",payload:a,cttAuthInfo:b.cttAuthInfo,
dangerousLogToVisitorSession:b.dangerousLogToVisitorSession},c)}
;var qt=new Set,rt=0,st=0,tt=0,ut=[],vt=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function Ln(a){wt(a)}
function xt(a){wt(a,"WARNING")}
function wt(a,b,c,d,e,f,g){f=void 0===f?{}:f;f.name=c||O("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||O("INNERTUBE_CONTEXT_CLIENT_VERSION");var h=f,l=void 0===b?"ERROR":b,m=void 0===g?!1:g;l=void 0===l?"ERROR":l;m=void 0===m?!1:m;if(a){a.hasOwnProperty("level")&&a.level&&(l=a.level);if(R("console_log_js_exceptions")){var p=[];p.push("Name: "+a.name);p.push("Message: "+a.message);a.hasOwnProperty("params")&&p.push("Error Params: "+JSON.stringify(a.params));a.hasOwnProperty("args")&&p.push("Error args: "+
JSON.stringify(a.args));p.push("File name: "+a.fileName);p.push("Stacktrace: "+a.stack);var r=p.join("\n");window.console.log(r,a)}if(!(5<=rt)){var y=ut,u=De(a),z=u.message||"Unknown Error",D=u.name||"UnknownError",G=u.stack||a.i||"Not available";if(G.startsWith(D+": "+z)){var M=G.split("\n");M.shift();G=M.join("\n")}var P=u.lineNumber||"Not available",T=u.fileName||"Not available",da=G,Z=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var na=0;na<a.args.length&&!(Z=Tm(a.args[na],"params."+
na,h,Z),500<=Z);na++);else if(a.hasOwnProperty("params")&&a.params){var La=a.params;if("object"===typeof a.params)for(var ya in La){if(La[ya]){var za="params."+ya,va=Vm(La[ya]);h[za]=va;Z+=za.length+va.length;if(500<Z)break}}else h.params=Vm(La)}if(y.length)for(var ma=0;ma<y.length&&!(Z=Tm(y[ma],"params.context."+ma,h,Z),500<=Z);ma++);navigator.vendor&&!h.hasOwnProperty("vendor")&&(h["device.vendor"]=navigator.vendor);var L={message:z,name:D,lineNumber:P,fileName:T,stack:da,params:h,sampleWeight:1},
jf=Number(a.columnNumber);isNaN(jf)||(L.lineNumber=L.lineNumber+":"+jf);if("IGNORED"===a.level)var Uc=0;else a:{for(var kf=Pm(),ja=t(kf.Va),lf=ja.next();!lf.done;lf=ja.next()){var xh=lf.value;if(L.message&&L.message.match(xh.If)){Uc=xh.weight;break a}}for(var Vq=t(kf.Sa),al=Vq.next();!al.done;al=Vq.next()){var Wq=al.value;if(Wq.callback(L)){Uc=Wq.weight;break a}}Uc=1}L.sampleWeight=Uc;for(var Xq=t(Km),bl=Xq.next();!bl.done;bl=Xq.next()){var cl=bl.value;if(cl.ic[L.name])for(var Yq=t(cl.ic[L.name]),
dl=Yq.next();!dl.done;dl=Yq.next()){var Zq=dl.value,yh=L.message.match(Zq.regexp);if(yh){L.params["params.error.original"]=yh[0];for(var el=Zq.groups,$q={},Pd=0;Pd<el.length;Pd++)$q[el[Pd]]=yh[Pd+1],L.params["params.error."+el[Pd]]=yh[Pd+1];L.message=cl.Hc($q);break}}}L.params||(L.params={});var ar=Pm();L.params["params.errorServiceSignature"]="msg="+ar.Va.length+"&cb="+ar.Sa.length;L.params["params.serviceWorker"]="false";x.document&&x.document.querySelectorAll&&(L.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));
Ab("sample").constructor!==yb&&(L.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(L);if(0!==L.sampleWeight&&!qt.has(L.message)){if(m&&R("web_enable_error_204"))zt(void 0===l?"ERROR":l,L);else{var Vc=l;Vc=void 0===Vc?"ERROR":Vc;if("ERROR"===Vc){Qm.bb("handleError",L);if(R("record_app_crashed_web")&&0===tt&&1===L.sampleWeight)if(tt++,R("errors_via_jspb")){var mx=new Zk;var cr=F(mx,1,1);if(!R("report_client_error_with_app_crash_ks")){var nx=new Yk,ox=new Xk,
px=new Wk,qx=new Vk;var rx=F(qx,1,L.message);var sx=H(px,Vk,3,rx);var tx=H(ox,Wk,5,sx);var ux=H(nx,Xk,9,tx);H(cr,Yk,4,ux)}var dr=R("jspb_sparse_encoded_pivot")?new Cl([{}]):new Cl;ce(dr,Zk,20,Dl,cr);pt(dr)}else{var er={appCrashType:"APP_CRASH_TYPE_BREAKPAD"};R("report_client_error_with_app_crash_ks")||(er.systemHealth={crashData:{clientError:{logMessage:{message:L.message}}}});Mn("appCrashed",er)}st++}else"WARNING"===Vc&&Qm.bb("handleWarning",L);if(R("kevlar_gel_error_routing"))a:{var mf=Vc;if(R("errors_via_jspb")){if(At())var gr=
void 0;else{var Qd=new Sk;F(Qd,1,L.stack);L.fileName&&F(Qd,4,L.fileName);var Rb=L.lineNumber&&L.lineNumber.split?L.lineNumber.split(":"):[];0!==Rb.length&&(1!==Rb.length||isNaN(Number(Rb[0]))?2!==Rb.length||isNaN(Number(Rb[0]))||isNaN(Number(Rb[1]))||(fe(Qd,2,Number(Rb[0])),fe(Qd,3,Number(Rb[1]))):fe(Qd,2,Number(Rb[0])));var Wc=new Vk;F(Wc,1,L.message);F(Wc,3,L.name);fe(Wc,6,L.sampleWeight);"ERROR"===mf?F(Wc,2,2):"WARNING"===mf?F(Wc,2,1):F(Wc,2,0);var fl=new Tk;F(fl,1,!0);ce(fl,Sk,3,Uk,Qd);var qc=
new Rk;F(qc,3,window.location.href);for(var hr=O("FEXP_EXPERIMENTS",[]),gl=0;gl<hr.length;gl++){var vx=hr[gl];Id(qc);Xd(qc,5,2,!1,!1).push(vx)}var hl=O("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Wl()&&hl)for(var ir=t(Object.keys(hl)),Xc=ir.next();!Xc.done;Xc=ir.next()){var jr=Xc.value,il=new Qk;F(il,1,jr);F(il,2,String(hl[jr]));ee(qc,4,Qk,il)}var jl=L.params;if(jl){var kr=t(Object.keys(jl));for(Xc=kr.next();!Xc.done;Xc=kr.next()){var lr=Xc.value,kl=new Qk;F(kl,1,"client."+lr);F(kl,2,String(jl[lr]));
ee(qc,4,Qk,kl)}}var mr=O("SERVER_NAME"),nr=O("SERVER_VERSION");if(mr&&nr){var ll=new Qk;F(ll,1,"server.name");F(ll,2,mr);ee(qc,4,Qk,ll);var ml=new Qk;F(ml,1,"server.version");F(ml,2,nr);ee(qc,4,Qk,ml)}var zh=new Wk;H(zh,Rk,1,qc);H(zh,Tk,2,fl);H(zh,Vk,3,Wc);gr=zh}var or=gr;if(!or)break a;var pr=R("jspb_sparse_encoded_pivot")?new Cl([{}]):new Cl;ce(pr,Wk,163,Dl,or);pt(pr)}else{if(At())var qr=void 0;else{var nf={stackTrace:L.stack};L.fileName&&(nf.filename=L.fileName);var Sb=L.lineNumber&&L.lineNumber.split?
L.lineNumber.split(":"):[];0!==Sb.length&&(1!==Sb.length||isNaN(Number(Sb[0]))?2!==Sb.length||isNaN(Number(Sb[0]))||isNaN(Number(Sb[1]))||(nf.lineNumber=Number(Sb[0]),nf.columnNumber=Number(Sb[1])):nf.lineNumber=Number(Sb[0]));var nl={level:"ERROR_LEVEL_UNKNOWN",message:L.message,errorClassName:L.name,sampleWeight:L.sampleWeight};"ERROR"===mf?nl.level="ERROR_LEVEL_ERROR":"WARNING"===mf&&(nl.level="ERROR_LEVEL_WARNNING");var wx={isObfuscated:!0,browserStackInfo:nf},Rd={pageUrl:window.location.href,
kvPairs:[]};O("FEXP_EXPERIMENTS")&&(Rd.experimentIds=O("FEXP_EXPERIMENTS"));var ol=O("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!Wl()&&ol)for(var rr=t(Object.keys(ol)),Yc=rr.next();!Yc.done;Yc=rr.next()){var sr=Yc.value;Rd.kvPairs.push({key:sr,value:String(ol[sr])})}var pl=L.params;if(pl){var tr=t(Object.keys(pl));for(Yc=tr.next();!Yc.done;Yc=tr.next()){var ur=Yc.value;Rd.kvPairs.push({key:"client."+ur,value:String(pl[ur])})}}var vr=O("SERVER_NAME"),wr=O("SERVER_VERSION");vr&&wr&&(Rd.kvPairs.push({key:"server.name",
value:vr}),Rd.kvPairs.push({key:"server.version",value:wr}));qr={errorMetadata:Rd,stackTrace:wx,logMessage:nl}}var xr=qr;if(!xr)break a;Mn("clientError",xr)}if("ERROR"===mf||R("errors_flush_gel_always_killswitch"))b:{if(R("web_fp_via_jspb")){var Ah=!0;Ah=void 0===Ah?!1:Ah;var yr=nt;nt=[];if(yr)for(var zr=t(yr),ql=zr.next();!ql.done;ql=zr.next()){var Sd=ql.value;Ah?kt(Sd.payloadName,Sd.payload,Er,Sd.options):Mn(Sd.payloadName,Sd.payload,Sd.options)}mt(!0);if(!R("web_fp_via_jspb_and_json"))break b}mt()}}R("suppress_error_204_logging")||
zt(Vc,L)}try{qt.add(L.message)}catch(ez){}rt++}}}}
function At(){for(var a=t(vt),b=a.next();!b.done;b=a.next())if(Sn(b.value.toLowerCase()))return!0;return!1}
function zt(a,b){var c=b.params||{};a={urlParams:{a:"logerror",t:"jserror",type:b.name,msg:b.message.substr(0,250),line:b.lineNumber,level:a,"client.name":c.name},postParams:{url:O("PAGE_NAME",window.location.href),file:b.fileName},method:"POST"};c.version&&(a["client.version"]=c.version);if(a.postParams){b.stack&&(a.postParams.stack=b.stack);b=t(Object.keys(c));for(var d=b.next();!d.done;d=b.next())d=d.value,a.postParams["client."+d]=c[d];if(c=O("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS"))for(b=t(Object.keys(c)),
d=b.next();!d.done;d=b.next())d=d.value,a.postParams[d]=c[d];c=O("SERVER_NAME");b=O("SERVER_VERSION");c&&b&&(a.postParams["server.name"]=c,a.postParams["server.version"]=b)}Bm(O("ECATCHER_REPORT_HOST","")+"/error_204",a)}
;function Bt(){this.register=new Map}
function Ct(a){a=t(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Lf("ABORTED")}
Bt.prototype.clear=function(){Ct(this);this.register.clear()};
var Dt=new Bt;var Et=Date.now().toString();
function Ft(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(Et)for(a=1,b=0;b<Et.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^Et.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var Gt=x.ytLoggingDocDocumentNonce_;Gt||(Gt=Ft(),A("ytLoggingDocDocumentNonce_",Gt));var Ht=Gt;function It(a){a=void 0===a?0:a;return 0===a?"client-screen-nonce":"client-screen-nonce."+a}
function Jt(a){a=void 0===a?0:a;return R("new_csn_storage_design")?O("client-screen-nonce-store",{})[a]:O(It(a))}
function Kt(a,b){b=void 0===b?0:b;if(R("new_csn_storage_design")){var c=O("client-screen-nonce-store");c||(c={},Vl("client-screen-nonce-store",c));c[b]=a}Vl(It(b),a)}
function Lt(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
A("yt_logging_screen.getRootVeType",function(a){return O(Lt(void 0===a?0:a))});
function Mt(){var a=O("csn-to-ctt-auth-info");a||(a={},Vl("csn-to-ctt-auth-info",a));return a}
function Nt(a){a=Jt(void 0===a?0:a);if(!a&&!O("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
A("yt_logging_screen.getCurrentCsn",Nt);function Ot(a,b,c){var d=Mt();(c=Nt(c))&&delete d[c];b&&(d[a]=b)}
A("yt_logging_screen.getCttAuthInfo",function(a){return Mt()[a]});
A("yt_logging_screen.setCurrentScreen",function(a,b,c,d){c=void 0===c?0:c;if(a!==Jt(c)||b!==O(Lt(c)))if(Ot(a,d,c),Kt(a,c),Vl(Lt(c),b),b=function(){setTimeout(function(){if(a)if(R("web_time_via_jspb")){var e=new rl;F(e,1,Ht);F(e,2,a);var f=R("jspb_sparse_encoded_pivot")?new Cl([{}]):new Cl;ce(f,rl,111,Dl,e);pt(f)}else Mn("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:Ht,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()});var Pt=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};A("yt.msgs_",Pt);function Qt(a){Ql(Pt,arguments)}
;function Rt(){var a=sb(St),b;return(new Gf(function(c,d){a.onSuccess=function(e){tm(e)?c(new Tt(e)):d(new Ut("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Ut("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new Ut("Request timed out","net.timeout",e))};
b=Bm("//googleads.g.doubleclick.net/pagead/id",a)})).oc(function(c){c instanceof Rf&&b.abort();
return Mf(c)})}
function Ut(a,b,c){bb.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
v(Ut,bb);function Tt(a){this.xhr=a}
;function Vt(){this.h=0;this.i=null}
Vt.prototype.then=function(a,b,c){return 1===this.h&&a?(a=a.call(c,this.i))&&"function"===typeof a.then?a:Wt(a):2===this.h&&b?(a=b.call(c,this.i))&&"function"===typeof a.then?a:Xt(a):this};
Vt.prototype.getValue=function(){return this.i};
Vt.prototype.isRejected=function(){return 2==this.h};
Vt.prototype.$goog_Thenable=!0;function Xt(a){var b=new Vt;a=void 0===a?null:a;b.h=2;b.i=void 0===a?null:a;return b}
function Wt(a){var b=new Vt;a=void 0===a?null:a;b.h=1;b.i=void 0===a?null:a;return b}
;function Yt(a,b){var c=void 0===c?{}:c;a={method:void 0===b?"POST":b,mode:km(a)?"same-origin":"cors",credentials:km(a)?"same-origin":"include"};b={};for(var d=t(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);0<Object.keys(b).length&&(a.headers=b);return a}
;function Zt(){return Gg()||(od||pd)&&Sn("applewebkit")&&!Sn("version")&&(!Sn("safari")||Sn("gsa/"))||ed&&Sn("version/")?!0:O("EOM_VISITOR_DATA")?!1:!0}
;function $t(a){a:{var b="EMBEDDED_PLAYER_MODE_UNKNOWN";window.location.hostname.includes("youtubeeducation.com")&&(b="EMBEDDED_PLAYER_MODE_PFL");var c=a.raw_embedded_player_response;if(!c&&(a=a.embedded_player_response))try{c=JSON.parse(a)}catch(e){break a}if(c)b:for(var d in Nk)if(Nk[d]==c.embeddedPlayerMode){b=Nk[d];break b}}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function au(a){bb.call(this,a.message||a.description||a.name);this.isMissing=a instanceof bu;this.isTimeout=a instanceof Ut&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Rf}
v(au,bb);au.prototype.name="BiscottiError";function bu(){bb.call(this,"Biscotti ID is missing from server")}
v(bu,bb);bu.prototype.name="BiscottiMissingError";var St={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},cu=null;function du(){if(R("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!Zt())return Error("User has not consented - not fetching biscotti id.");var a=O("PLAYER_VARS",{});if("1"==qb(a))return Error("Biscotti ID is not available in private embed mode");if($t(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function Ol(){var a=du();if(void 0!==a)return Mf(a);cu||(cu=Rt().then(eu).oc(function(b){return fu(2,b)}));
return cu}
function eu(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new bu;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new bu;a=a.id;Pl(a);cu=Wt(a);gu(18E5,2);return a}
function fu(a,b){b=new au(b);Pl("");cu=Xt(b);0<a&&gu(12E4,a-1);throw b;}
function gu(a,b){um(function(){Rt().then(eu,function(c){return fu(b,c)}).oc(db)},a)}
function hu(){try{var a=B("yt.ads.biscotti.getId_");return a?a():Ol()}catch(b){return Mf(b)}}
;function iu(a){if("1"!=qb(O("PLAYER_VARS",{}))){a&&Nl();try{hu().then(function(){},function(){}),um(iu,18E5)}catch(b){$l(b)}}}
;function ju(){var a=hn(),b=ln(119),c=1<window.devicePixelRatio;if(document.body&&Ci(document.body,"exp-invert-logo"))if(c&&!Ci(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Ci(d,"inverted-hdpi")){var e=Ai(d);Bi(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Ci(document.body,"inverted-hdpi")&&Di();if(b!=c){b="f"+(Math.floor(119/31)+1);d=mn(b)||0;d=c?d|67108864:d&-67108865;0===d?delete en[b]:(c=d.toString(16),en[b]=c.toString());
c=!0;R("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(f in en)en.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(en[f])));var f=d.join("&");bn(b,f,63072E3,a.i,c)}}
;var ku=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function lu(){var a=void 0===a?window.location.href:a;if(R("kevlar_disable_theme_param"))return null;vc(wc(5,a));try{var b=im(a).theme;return ku.get(b)||null}catch(c){}return null}
;function mu(){this.h={};if(this.i=dn()){var a=Eg.get("CONSISTENCY",void 0);a&&nu(this,{encryptedTokenJarContents:a})}}
mu.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.Oa.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=t(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];nu(this,a)}};
function nu(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},1E3*c);
a.i&&bn("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var ou=window.location.hostname.split(".").slice(-2).join(".");function pu(){var a=O("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===O("INNERTUBE_CLIENT_NAME")&&(this.h=qu(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var ru;function su(){ru=B("yt.clientLocationService.instance");ru||(ru=new pu,A("yt.clientLocationService.instance",ru));return ru}
k=pu.prototype;k.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.i?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.i.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.i.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
k.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.i=void 0,"TVHTML5"===O("INNERTUBE_CLIENT_NAME")?(this.h=qu(this))&&this.h.set("yt-location-playability-token",a,15552E3):bn("YT_CL",JSON.stringify({loctok:a}),15552E3,ou,!0))};
function qu(a){return void 0===a.h?new Dn("yt-client-location"):a.h}
k.clearLocationPlayabilityToken=function(a){"TVHTML5"===a?(this.h=qu(this))&&this.h.remove("yt-location-playability-token"):cn("YT_CL")};
k.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;"MWEB"===O("INNERTUBE_CLIENT_NAME")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
k.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};function tu(a,b){if(!a)return!1;var c,d=null==(c=ts(a,Mk))?void 0:c.signal;if(d&&b.jb)return!!b.jb[d];var e;if((c=null==(e=ts(a,Jk))?void 0:e.request)&&b.uc)return!!b.uc[c];for(var f in a)if(b.sc[f])return!0;return!1}
function uu(a,b){var c,d=null==(c=ts(a,Mk))?void 0:c.signal;if(d&&b.jb&&(c=b.jb[d]))return c();var e;if((c=null==(e=ts(a,Jk))?void 0:e.request)&&b.uc&&(e=b.uc[c]))return e();for(var f in a)if(b.sc[f]&&(a=b.sc[f]))return a()}
;function vu(a){return function(){return new a}}
;var wu={},xu=(wu.WEB_UNPLUGGED="^unplugged/",wu.WEB_UNPLUGGED_ONBOARDING="^unplugged/",wu.WEB_UNPLUGGED_OPS="^unplugged/",wu.WEB_UNPLUGGED_PUBLIC="^unplugged/",wu.WEB_CREATOR="^creator/",wu.WEB_KIDS="^kids/",wu.WEB_EXPERIMENTS="^experiments/",wu.WEB_MUSIC="^music/",wu.WEB_REMIX="^music/",wu.WEB_MUSIC_EMBEDDED_PLAYER="^music/",wu.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",wu);
function yu(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=xu[b];if(c){var d=new RegExp(c),e=t(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(xu).forEach(function(g){var h=t(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=t(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function zu(){}
zu.prototype.m=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?Zm:c;var d=a.clickTrackingParams,e=this.l,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=O("INNERTUBE_CONTEXT");if(g){g=tb(g);R("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=O("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var l=void 0===l?!1:l;hn();var m="USER_INTERFACE_THEME_LIGHT";ln(165)?m="USER_INTERFACE_THEME_DARK":ln(174)?m="USER_INTERFACE_THEME_LIGHT":!R("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(m="USER_INTERFACE_THEME_DARK");l=l?m:lu()||m;h.userInterfaceTheme=l;if(!f){if(l=sn())h.connectionType=
l;R("web_log_effective_connection_type")&&(l=tn())&&(g.client.effectiveConnectionType=l)}var p;if(R("web_log_memory_total_kbytes")&&(null==(p=x.navigator)?0:p.deviceMemory)){var r;p=null==(r=x.navigator)?void 0:r.deviceMemory;g.client.memoryTotalKbytes=""+1E6*p}r=im(x.location.href);!R("web_populate_internal_geo_killswitch")&&r.internalcountrycode&&(h.internalGeo=r.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:x.location.href},R("kevlar_woffle")&&$m.h&&
(r=$m.h,h.mainAppWebInfo.pwaInstallabilityStatus=!r.h&&r.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=an(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):"TVHTML5"===h.clientName&&(!R("web_lr_app_quality_killswitch")&&(r=O("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:r})),r=O("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{certificationScope:r}));
if(!R("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var y=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(na){}y=void 0}y&&(h.timeZone=y)}(y=pm())?h.experimentsToken=y:delete h.experimentsToken;y=qm();mu.h||(mu.h=new mu);h=mu.h.h;r=[];p=0;for(var u in h)r[p++]=h[u];g.request=Object.assign({},g.request,{internalExperimentFlags:y,consistencyTokenJars:r});!R("web_prequest_context_killswitch")&&(u=O("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(g.request.externalPrequestContext=
u);y=hn();u=ln(58);y=y.get("gsml","");g.user=Object.assign({},g.user);u&&(g.user.enableSafetyMode=u);y&&(g.user.lockedSafetyMode=!0);R("warm_op_csn_cleanup")?e&&(f=Nt())&&(g.clientScreenNonce=f):!f&&(f=Nt())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=B("yt.mdx.remote.remoteClient_"))g.remoteClient=d;su().setLocationOnInnerTubeContext(g);try{var z=lm(),D=z.bid;delete z.bid;g.adSignalsInfo={params:[],bid:D};var G=t(Object.entries(z));for(var M=G.next();!M.done;M=G.next()){var P=
t(M.value),T=P.next().value,da=P.next().value;z=T;D=da;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:z,value:""+D})}}catch(na){wt(na)}G=g}else wt(Error("Error: No InnerTubeContext shell provided in ytconfig.")),G={};G={context:G};if(M=this.h(a)){this.i(G,M,b);var Z;b="/youtubei/v1/"+yu(this.j());(M=null==(Z=ts(a.commandMetadata,Lk))?void 0:Z.apiUrl)&&(b=M);Z=b;(b=O("INNERTUBE_HOST_OVERRIDE"))&&(Z=String(b)+String(yc(Z)));b={};b.key=O("INNERTUBE_API_KEY");R("json_condensed_response")&&(b.prettyPrint=
"false");Z=jm(Z,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:Z,hb:Yt(Z),Oa:G,config:a};a.config.Vb?a.config.Vb.identity=c:a.config.Vb={identity:c};return a}wt(new un("Error: Failed to create Request from Command.",a))};
ea.Object.defineProperties(zu.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!1}}});function Au(){}
v(Au,zu);Au.prototype.m=function(){return{input:"/getDatasyncIdsEndpoint",hb:Yt("/getDatasyncIdsEndpoint","GET"),Oa:{}}};
Au.prototype.j=function(){return[]};
Au.prototype.h=function(){};
Au.prototype.i=function(){};var Bu={},Cu=(Bu.GET_DATASYNC_IDS=vu(Au),Bu);function Du(a){var b=Ma.apply(1,arguments);if(!Eu(a)||b.some(function(d){return!Eu(d)}))throw Error("Only objects may be merged.");
b=t(b);for(var c=b.next();!c.done;c=b.next())Fu(a,c.value);return a}
function Fu(a,b){for(var c in b)if(Eu(b[c])){if(c in a&&!Eu(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});Fu(a[c],b[c])}else if(Gu(b[c])){if(c in a&&!Gu(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);Hu(a[c],b[c])}else a[c]=b[c];return a}
function Hu(a,b){b=t(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Eu(c)?a.push(Fu({},c)):Gu(c)?a.push(Hu([],c)):a.push(c);return a}
function Eu(a){return"object"===typeof a&&!Array.isArray(a)}
function Gu(a){return"object"===typeof a&&Array.isArray(a)}
;function Iu(a){var b;(b=B("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},A("ytcsi."+(a||"")+"data_",b));return b}
function Ju(){var a=Iu();a.info||(a.info={});return a.info}
function Ku(a){a=Iu(a);a.metadata||(a.metadata={});return a.metadata}
function Lu(a){a=Iu(a);a.tick||(a.tick={});return a.tick}
function Mu(a){a=Iu(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function Nu(a){a=Mu(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function Ou(a){var b=Iu(a).nonce;b||(b=Ft(),Iu(a).nonce=b);return b}
;function Pu(){var a=B("ytcsi.debug");a||(a=[],A("ytcsi.debug",a),A("ytcsi.reference",{}));return a}
function Qu(a){a=a||"";var b=B("ytcsi.reference");b||(Pu(),b=B("ytcsi.reference"));if(b[a])return b[a];var c=Pu(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var U={},Ru=(U.auto_search="LATENCY_ACTION_AUTO_SEARCH",U.ad_to_ad="LATENCY_ACTION_AD_TO_AD",U.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",U["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",U.app_startup="LATENCY_ACTION_APP_STARTUP",U["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",U["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",U["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",U["asset.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS",
U["asset.composition"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION",U["asset.embeds"]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS",U["asset.issues"]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES",U["asset.licenses"]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES",U["asset.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA",U["asset.ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP",U["asset.policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY",U["asset.references"]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES",
U["asset.sound_recordings"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS",U["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",U.browse="LATENCY_ACTION_BROWSE",U.cast_splash="LATENCY_ACTION_CAST_SPLASH",U.channels="LATENCY_ACTION_CHANNELS",U.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",U["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",U["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",U["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",
U["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",U["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",U["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",U["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",U["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",U["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",U["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",U["channel.translations"]=
"LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",U["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",U["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",U.chips="LATENCY_ACTION_CHIPS",U["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",U["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",U["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",U.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",U.embed="LATENCY_ACTION_EMBED",
U.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",U.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",U.explore="LATENCY_ACTION_EXPLORE",U.home="LATENCY_ACTION_HOME",U.library="LATENCY_ACTION_LIBRARY",U.live="LATENCY_ACTION_LIVE",U.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",U.onboarding="LATENCY_ACTION_ONBOARDING",U.owner="LATENCY_ACTION_CREATOR_CMS_DASHBOARD",U["owner.allowlist"]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST",U["owner.analytics"]=
"LATENCY_ACTION_CREATOR_CMS_ANALYTICS",U["owner.art_tracks"]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS",U["owner.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSETS",U["owner.asset_groups"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS",U["owner.campaigns"]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS",U["owner.channels"]="LATENCY_ACTION_CREATOR_CMS_CHANNELS",U["owner.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS",U["owner.claims"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",U["owner.claims.manual"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",
U["owner.delivery"]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY",U["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",U["owner.licenses"]="LATENCY_ACTION_CREATOR_CMS_LICENSES",U["owner.pitch_music"]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC",U["owner.policies"]="LATENCY_ACTION_CREATOR_CMS_POLICIES",U["owner.releases"]="LATENCY_ACTION_CREATOR_CMS_RELEASES",U["owner.reports"]="LATENCY_ACTION_CREATOR_CMS_REPORTS",U["owner.videos"]="LATENCY_ACTION_CREATOR_CMS_VIDEOS",U.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",
U.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",U.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",U.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",U["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",U["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",U.prebuffer="LATENCY_ACTION_PREBUFFER",U.prefetch="LATENCY_ACTION_PREFETCH",U.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",U.profile_switcher="LATENCY_ACTION_LOGIN",U.reel_watch="LATENCY_ACTION_REEL_WATCH",
U.results="LATENCY_ACTION_RESULTS",U["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",U.search_ui="LATENCY_ACTION_SEARCH_UI",U.search_suggest="LATENCY_ACTION_SUGGEST",U.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",U.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",U.seek="LATENCY_ACTION_PLAYER_SEEK",U.settings="LATENCY_ACTION_SETTINGS",U.store="LATENCY_ACTION_STORE",U.tenx="LATENCY_ACTION_TENX",U.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",U.watch="LATENCY_ACTION_WATCH",U.watch_it_again=
"LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",U["watch,watch7"]="LATENCY_ACTION_WATCH",U["watch,watch7_html5"]="LATENCY_ACTION_WATCH",U["watch,watch7ad"]="LATENCY_ACTION_WATCH",U["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",U.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",U.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",U["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",U["video.claims"]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS",U["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",U["video.copyright"]=
"LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT",U["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",U["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",U["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",U["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",U["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",U["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",U["video.policy"]="LATENCY_ACTION_CREATOR_VIDEO_POLICY",U["video.rights_management"]=
"LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT",U["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",U.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",U.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",U.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",U.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",U.gel_jspb_serialize="LATENCY_ACTION_GEL_JSPB_SERIALIZE",U),V={},Su=(V.ad_allowed="adTypesAllowed",V.yt_abt="adBreakType",V.ad_cpn="adClientPlaybackNonce",
V.ad_docid="adVideoId",V.yt_ad_an="adNetworks",V.ad_at="adType",V.aida="appInstallDataAgeMs",V.browse_id="browseId",V.p="httpProtocol",V.t="transportProtocol",V.cs="commandSource",V.cpn="clientPlaybackNonce",V.ccs="creatorInfo.creatorCanaryState",V.ctop="creatorInfo.topEntityType",V.csn="clientScreenNonce",V.docid="videoId",V.GetHome_rid="requestIds",V.GetSearch_rid="requestIds",V.GetPlayer_rid="requestIds",V.GetWatchNext_rid="requestIds",V.GetBrowse_rid="requestIds",V.GetLibrary_rid="requestIds",
V.is_continuation="isContinuation",V.is_nav="isNavigation",V.b_p="kabukiInfo.browseParams",V.is_prefetch="kabukiInfo.isPrefetch",V.is_secondary_nav="kabukiInfo.isSecondaryNav",V.nav_type="kabukiInfo.navigationType",V.prev_browse_id="kabukiInfo.prevBrowseId",V.query_source="kabukiInfo.querySource",V.voz_type="kabukiInfo.vozType",V.yt_lt="loadType",V.mver="creatorInfo.measurementVersion",V.yt_ad="isMonetized",V.nr="webInfo.navigationReason",V.nrsu="navigationRequestedSameUrl",V.pnt="performanceNavigationTiming",
V.prt="playbackRequiresTap",V.plt="playerInfo.playbackType",V.pis="playerInfo.playerInitializedState",V.paused="playerInfo.isPausedOnLoad",V.yt_pt="playerType",V.fmt="playerInfo.itag",V.yt_pl="watchInfo.isPlaylist",V.yt_pre="playerInfo.preloadType",V.yt_ad_pr="prerollAllowed",V.pa="previousAction",V.yt_red="isRedSubscriber",V.rce="mwebInfo.responseContentEncoding",V.rc="resourceInfo.resourceCache",V.scrh="screenHeight",V.scrw="screenWidth",V.st="serverTimeMs",V.ssdm="shellStartupDurationMs",V.br_trs=
"tvInfo.bedrockTriggerState",V.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",V.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",V.label="tvInfo.label",V.is_mdx="tvInfo.isMdx",V.preloaded="tvInfo.isPreloaded",V.aac_type="tvInfo.authAccessCredentialType",V.upg_player_vis="playerInfo.visibilityState",V.query="unpluggedInfo.query",V.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",V.yt_vst="videoStreamType",V.vph="viewportHeight",V.vpw="viewportWidth",V.yt_vis="isVisible",V.rcl="mwebInfo.responseContentLength",
V.GetSettings_rid="requestIds",V.GetTrending_rid="requestIds",V.GetMusicSearchSuggestions_rid="requestIds",V.REQUEST_ID="requestIds",V),Tu="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),Uu={},Vu=(Uu.ccs="CANARY_STATE_",
Uu.mver="MEASUREMENT_VERSION_",Uu.pis="PLAYER_INITIALIZED_STATE_",Uu.yt_pt="LATENCY_PLAYER_",Uu.pa="LATENCY_ACTION_",Uu.ctop="TOP_ENTITY_TYPE_",Uu.yt_vst="VIDEO_STREAM_TYPE_",Uu),Wu="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function Xu(a){return Ru[a]||"LATENCY_ACTION_UNKNOWN"}
function Yu(a,b,c){c=Mu(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in Su){c=Su[a];0<=fb(Tu,c)&&(b=!!b);a in Vu&&"string"===typeof b&&(b=Vu[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Du({},d)}0<=fb(Wu,a)||xt(new un("Unknown label logged with GEL CSI",a))}
;var W={LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING:179,LATENCY_ACTION_KIDS_PROFILE_SWITCHER:90,LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER:100,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC:46,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR:37,LATENCY_ACTION_SPINNER_DISPLAYED:14,LATENCY_ACTION_PLAYABILITY_CHECK:10,LATENCY_ACTION_PROCESS:9,LATENCY_ACTION_APP_STARTUP:5,LATENCY_ACTION_MINI_APP_PLAY:249,LATENCY_ACTION_DMA_CONSENT_FLOW:247,LATENCY_ACTION_GEL_FETCH:248,LATENCY_ACTION_GEL_JSPB_SERIALIZE:243,
LATENCY_ACTION_GEL_COMPRESSION:215,LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE:204,LATENCY_ACTION_COMMERCE_ACTION_COMMAND_RPC:203,LATENCY_ACTION_COMMERCE_TRANSACTION:184,LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC:173,LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC:172,LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC:171,LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC:170,LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC:169,LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC:168,LATENCY_ACTION_GET_OFFERS_RPC:167,LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC:166,
LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC:165,LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC:164,LATENCY_ACTION_GET_OFFER_DETAILS_RPC:163,LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC:162,LATENCY_ACTION_GET_TIP_MODULE_RPC:161,LATENCY_ACTION_HANDLE_TRANSACTION_RPC:160,LATENCY_ACTION_COMPLETE_TRANSACTION_RPC:159,LATENCY_ACTION_GET_CART_RPC:158,LATENCY_ACTION_THUMBNAIL_FETCH:156,LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK:154,LATENCY_ACTION_SHARE_VIDEO:153,LATENCY_ACTION_AD_TO_VIDEO_INT:152,LATENCY_ACTION_ABANDONED_BROWSE:151,
LATENCY_ACTION_PLAYER_ROTATION:150,LATENCY_ACTION_GENERIC_WEB_VIEW:183,LATENCY_ACTION_SHOPPING_IN_APP:124,LATENCY_ACTION_PLAYER_ATTESTATION:121,LATENCY_ACTION_PLAYER_SEEK:119,LATENCY_ACTION_SUPER_STICKER_BUY_FLOW:114,LATENCY_ACTION_DOWNLOADS_DATA_ACCESS:180,LATENCY_ACTION_BLOCKS_PERFORMANCE:148,LATENCY_ACTION_ASSISTANT_QUERY:138,LATENCY_ACTION_ASSISTANT_SETTINGS:137,LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF:129,LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF:128,LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN:244,
LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE:127,LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION:123,LATENCY_ACTION_NETWORKLESS_PERFORMANCE:122,LATENCY_ACTION_DOWNLOADS_EXPANSION:133,LATENCY_ACTION_ENTITY_TRANSFORM:131,LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER:96,LATENCY_ACTION_EMBEDS_SET_VIDEO:95,LATENCY_ACTION_SETTINGS:93,LATENCY_ACTION_ABANDONED_STARTUP:81,LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY:80,LATENCY_ACTION_MEDIA_BROWSER_SEARCH:79,LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE:78,LATENCY_ACTION_WHO_IS_WATCHING:77,
LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH:76,LATENCY_ACTION_LITE_SWITCH_ACCOUNT:73,LATENCY_ACTION_ELEMENTS_PERFORMANCE:70,LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION:69,LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION:65,LATENCY_ACTION_OFFLINE_STORE_START:61,LATENCY_ACTION_REEL_EDITOR:58,LATENCY_ACTION_CHANNEL_SUBSCRIBE:56,LATENCY_ACTION_CHANNEL_PREVIEW:55,LATENCY_ACTION_PREFETCH:52,LATENCY_ACTION_ABANDONED_WATCH:45,LATENCY_ACTION_LOAD_COMMENT_REPLIES:26,LATENCY_ACTION_LOAD_COMMENTS:25,LATENCY_ACTION_EDIT_COMMENT:24,
LATENCY_ACTION_NEW_COMMENT:23,LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING:19,LATENCY_ACTION_EMBED:18,LATENCY_ACTION_MDX_LAUNCH:15,LATENCY_ACTION_RESOLVE_URL:13,LATENCY_ACTION_CAST_SPLASH:149,LATENCY_ACTION_MDX_CONNECT_TO_SESSION:190,LATENCY_ACTION_MDX_STREAM_TRANSFER:178,LATENCY_ACTION_MDX_CAST:120,LATENCY_ACTION_MDX_COMMAND:12,LATENCY_ACTION_MOBILE_LIVE_NAV_MDE:231,LATENCY_ACTION_REEL_SELECT_SEGMENT:136,LATENCY_ACTION_ACCELERATED_EFFECTS:145,LATENCY_ACTION_SHORTS_LOAD_PROJECT:234,LATENCY_ACTION_SHORTS_TRIM_TO_EDITOR_TRANSCODING:229,
LATENCY_ACTION_EDIT_AUDIO_GEN:182,LATENCY_ACTION_UPLOAD_AUDIO_MIXER:147,LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING:157,LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING:146,LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK:130,LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD:125,LATENCY_ACTION_SHORTS_CAMERA_AUDIO_DOWNLOAD:240,LATENCY_ACTION_SHORTS_VIDEO_INGESTION:155,LATENCY_ACTION_SHORTS_GALLERY:107,LATENCY_ACTION_SHORTS_TRIM:105,LATENCY_ACTION_SHORTS_EDIT:104,LATENCY_ACTION_SHORTS_CAMERA:103,LATENCY_ACTION_NON_CREATION_MODES_GLOBAL_ENTRYPOINT:239,
LATENCY_ACTION_CREATION_MODES_MODE_SWITCH:236,LATENCY_ACTION_CREATION_MODES_GLOBAL_ENTRYPOINT:235,LATENCY_ACTION_SWITCH_CAMERA:246,LATENCY_ACTION_OPEN_CAMERA:245,LATENCY_ACTION_MEDIA_ENGINE_DISPLAY_FIRST_FRAME:242,LATENCY_ACTION_MEDIA_ENGINE_EXPORT:241,LATENCY_ACTION_PRODUCER_IMPORT_LOCAL_MEDIA:233,LATENCY_ACTION_PRODUCER_EXPORT_PROJECT:193,LATENCY_ACTION_PRODUCER_EDITOR:192,LATENCY_ACTION_PARENT_TOOLS_DASHBOARD:102,LATENCY_ACTION_PARENT_TOOLS_COLLECTION:101,LATENCY_ACTION_MUSIC_OFFLINE_PLAYLIST_DETAIL:238,
LATENCY_ACTION_MUSIC_OFFLINE_ALBUM_DETAIL:237,LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS:116,LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS:115,LATENCY_ACTION_MUSIC_ALBUM_DETAIL:72,LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL:71,LATENCY_ACTION_STORE:175,LATENCY_ACTION_CHIPS:68,LATENCY_ACTION_SEARCH_ZERO_STATE:67,LATENCY_ACTION_LIVE_PAGINATION:117,LATENCY_ACTION_LIVE:20,LATENCY_ACTION_PREBUFFER:40,LATENCY_ACTION_TENX:39,LATENCY_ACTION_KIDS_PROFILE_SETTINGS:94,LATENCY_ACTION_KIDS_WATCH_IT_AGAIN:92,LATENCY_ACTION_KIDS_SECRET_CODE:91,
LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS:89,LATENCY_ACTION_KIDS_ONBOARDING:88,LATENCY_ACTION_KIDS_VOICE_SEARCH:82,LATENCY_ACTION_KIDS_CURATED_COLLECTION:62,LATENCY_ACTION_KIDS_LIBRARY:53,LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS:38,LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT:219,LATENCY_ACTION_CREATOR_VIDEO_POLICY:217,LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION:74,LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING:141,LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS:142,LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC:51,
LATENCY_ACTION_CREATOR_VIDEO_EDITOR:50,LATENCY_ACTION_CREATOR_VIDEO_EDIT:36,LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT:218,LATENCY_ACTION_CREATOR_VIDEO_COMMENTS:34,LATENCY_ACTION_CREATOR_VIDEO_CLAIMS:216,LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS:33,LATENCY_ACTION_CREATOR_SONG_ANALYTICS:176,LATENCY_ACTION_CREATOR_PROMOTION_LIST:186,LATENCY_ACTION_CREATOR_PROMOTION_EDIT:185,LATENCY_ACTION_CREATOR_POST_LIST:112,LATENCY_ACTION_CREATOR_POST_EDIT:110,LATENCY_ACTION_CREATOR_POST_COMMENTS:111,LATENCY_ACTION_CREATOR_LIVE_STREAMING:108,
LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT:174,LATENCY_ACTION_CREATOR_DIALOG_UPLOADS:86,LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES:87,LATENCY_ACTION_CREATOR_CMS_VIDEOS:202,LATENCY_ACTION_CREATOR_CMS_REPORTS:201,LATENCY_ACTION_CREATOR_CMS_RELEASES:226,LATENCY_ACTION_CREATOR_CMS_POLICIES:225,LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC:224,LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING:200,LATENCY_ACTION_CREATOR_CMS_LICENSES:223,LATENCY_ACTION_CREATOR_CMS_ISSUES:191,LATENCY_ACTION_CREATOR_CMS_DASHBOARD:199,
LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY:198,LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS:197,LATENCY_ACTION_CREATOR_CMS_CHANNELS:196,LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS:222,LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS:214,LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES:209,LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY:208,LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP:207,LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA:205,LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES:212,LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES:206,
LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS:221,LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS:210,LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION:213,LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS:211,LATENCY_ACTION_CREATOR_CMS_ASSETS:195,LATENCY_ACTION_CREATOR_CMS_ART_TRACKS:220,LATENCY_ACTION_CREATOR_CMS_ANALYTICS:194,LATENCY_ACTION_CREATOR_CMS_ALLOWLIST:227,LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS:32,LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS:48,LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS:139,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT:177,
LATENCY_ACTION_CREATOR_CHANNEL_MUSIC:99,LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION:43,LATENCY_ACTION_CREATOR_CHANNEL_EDITING:113,LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD:49,LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT:44,LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS:66,LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS:31,LATENCY_ACTION_CREATOR_ARTIST_PROFILE:85,LATENCY_ACTION_CREATOR_ARTIST_CONCERTS:84,LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS:83,LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE:140,LATENCY_ACTION_EXPERIMENTAL_WATCH_UI:181,
LATENCY_ACTION_FINE_SCRUBBING_THUMBNAILS:228,LATENCY_ACTION_STORYBOARD_THUMBNAILS:118,LATENCY_ACTION_SEARCH_THUMBNAILS:59,LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD:54,LATENCY_ACTION_VOICE_ASSISTANT:47,LATENCY_ACTION_SEARCH_UI:35,LATENCY_ACTION_SUGGEST:30,LATENCY_ACTION_AUTO_SEARCH:126,LATENCY_ACTION_DOWNLOADS:98,LATENCY_ACTION_EXPLORE:75,LATENCY_ACTION_VIDEO_LIST:63,LATENCY_ACTION_HOME_RESUME:60,LATENCY_ACTION_SUBSCRIPTIONS_LIST:57,LATENCY_ACTION_THUMBNAIL_LOAD:42,LATENCY_ACTION_FIRST_THUMBNAIL_LOAD:29,
LATENCY_ACTION_SUBSCRIPTIONS_FEED:109,LATENCY_ACTION_SUBSCRIPTIONS:28,LATENCY_ACTION_TRENDING:27,LATENCY_ACTION_LIBRARY:21,LATENCY_ACTION_VIDEO_THUMBNAIL:8,LATENCY_ACTION_SHOW_MORE:7,LATENCY_ACTION_VIDEO_PREVIEW:6,LATENCY_ACTION_AD_TO_AD:22,LATENCY_ACTION_VIDEO_TO_AD:17,LATENCY_ACTION_AD_TO_VIDEO:16,LATENCY_ACTION_DIRECT_PLAYBACK:132,LATENCY_ACTION_PREBUFFER_VIDEO:144,LATENCY_ACTION_PREFETCH_VIDEO:143,LATENCY_ACTION_STARTUP:106,LATENCY_ACTION_INLINE_TO_WATCH:232,LATENCY_ACTION_MUSIC_IMMERSIVE_WATCH:230,
LATENCY_ACTION_ONBOARDING:135,LATENCY_ACTION_LOGIN:97,LATENCY_ACTION_REEL_WATCH:41,LATENCY_ACTION_WATCH:3,LATENCY_ACTION_RESULTS:2,LATENCY_ACTION_CHANNELS:4,LATENCY_ACTION_HOME:1,LATENCY_ACTION_BROWSE:11,LATENCY_ACTION_USER_ACTION:189,LATENCY_ACTION_INFRASTRUCTURE:188,LATENCY_ACTION_PAGE_NAVIGATION:187,LATENCY_ACTION_UNKNOWN:0};W[W.LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING";W[W.LATENCY_ACTION_KIDS_PROFILE_SWITCHER]="LATENCY_ACTION_KIDS_PROFILE_SWITCHER";
W[W.LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER]="LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER";W[W.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC";W[W.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR";W[W.LATENCY_ACTION_SPINNER_DISPLAYED]="LATENCY_ACTION_SPINNER_DISPLAYED";W[W.LATENCY_ACTION_PLAYABILITY_CHECK]="LATENCY_ACTION_PLAYABILITY_CHECK";W[W.LATENCY_ACTION_PROCESS]="LATENCY_ACTION_PROCESS";
W[W.LATENCY_ACTION_APP_STARTUP]="LATENCY_ACTION_APP_STARTUP";W[W.LATENCY_ACTION_MINI_APP_PLAY]="LATENCY_ACTION_MINI_APP_PLAY";W[W.LATENCY_ACTION_DMA_CONSENT_FLOW]="LATENCY_ACTION_DMA_CONSENT_FLOW";W[W.LATENCY_ACTION_GEL_FETCH]="LATENCY_ACTION_GEL_FETCH";W[W.LATENCY_ACTION_GEL_JSPB_SERIALIZE]="LATENCY_ACTION_GEL_JSPB_SERIALIZE";W[W.LATENCY_ACTION_GEL_COMPRESSION]="LATENCY_ACTION_GEL_COMPRESSION";W[W.LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE]="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE";
W[W.LATENCY_ACTION_COMMERCE_ACTION_COMMAND_RPC]="LATENCY_ACTION_COMMERCE_ACTION_COMMAND_RPC";W[W.LATENCY_ACTION_COMMERCE_TRANSACTION]="LATENCY_ACTION_COMMERCE_TRANSACTION";W[W.LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC]="LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC";W[W.LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC]="LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC";W[W.LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC]="LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC";
W[W.LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC]="LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC";W[W.LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC]="LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC";W[W.LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC]="LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC";W[W.LATENCY_ACTION_GET_OFFERS_RPC]="LATENCY_ACTION_GET_OFFERS_RPC";W[W.LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC";W[W.LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC";
W[W.LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC]="LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC";W[W.LATENCY_ACTION_GET_OFFER_DETAILS_RPC]="LATENCY_ACTION_GET_OFFER_DETAILS_RPC";W[W.LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC]="LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC";W[W.LATENCY_ACTION_GET_TIP_MODULE_RPC]="LATENCY_ACTION_GET_TIP_MODULE_RPC";W[W.LATENCY_ACTION_HANDLE_TRANSACTION_RPC]="LATENCY_ACTION_HANDLE_TRANSACTION_RPC";
W[W.LATENCY_ACTION_COMPLETE_TRANSACTION_RPC]="LATENCY_ACTION_COMPLETE_TRANSACTION_RPC";W[W.LATENCY_ACTION_GET_CART_RPC]="LATENCY_ACTION_GET_CART_RPC";W[W.LATENCY_ACTION_THUMBNAIL_FETCH]="LATENCY_ACTION_THUMBNAIL_FETCH";W[W.LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK]="LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK";W[W.LATENCY_ACTION_SHARE_VIDEO]="LATENCY_ACTION_SHARE_VIDEO";W[W.LATENCY_ACTION_AD_TO_VIDEO_INT]="LATENCY_ACTION_AD_TO_VIDEO_INT";W[W.LATENCY_ACTION_ABANDONED_BROWSE]="LATENCY_ACTION_ABANDONED_BROWSE";
W[W.LATENCY_ACTION_PLAYER_ROTATION]="LATENCY_ACTION_PLAYER_ROTATION";W[W.LATENCY_ACTION_GENERIC_WEB_VIEW]="LATENCY_ACTION_GENERIC_WEB_VIEW";W[W.LATENCY_ACTION_SHOPPING_IN_APP]="LATENCY_ACTION_SHOPPING_IN_APP";W[W.LATENCY_ACTION_PLAYER_ATTESTATION]="LATENCY_ACTION_PLAYER_ATTESTATION";W[W.LATENCY_ACTION_PLAYER_SEEK]="LATENCY_ACTION_PLAYER_SEEK";W[W.LATENCY_ACTION_SUPER_STICKER_BUY_FLOW]="LATENCY_ACTION_SUPER_STICKER_BUY_FLOW";W[W.LATENCY_ACTION_DOWNLOADS_DATA_ACCESS]="LATENCY_ACTION_DOWNLOADS_DATA_ACCESS";
W[W.LATENCY_ACTION_BLOCKS_PERFORMANCE]="LATENCY_ACTION_BLOCKS_PERFORMANCE";W[W.LATENCY_ACTION_ASSISTANT_QUERY]="LATENCY_ACTION_ASSISTANT_QUERY";W[W.LATENCY_ACTION_ASSISTANT_SETTINGS]="LATENCY_ACTION_ASSISTANT_SETTINGS";W[W.LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF";W[W.LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF";W[W.LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN]="LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN";
W[W.LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE]="LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE";W[W.LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION]="LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION";W[W.LATENCY_ACTION_NETWORKLESS_PERFORMANCE]="LATENCY_ACTION_NETWORKLESS_PERFORMANCE";W[W.LATENCY_ACTION_DOWNLOADS_EXPANSION]="LATENCY_ACTION_DOWNLOADS_EXPANSION";W[W.LATENCY_ACTION_ENTITY_TRANSFORM]="LATENCY_ACTION_ENTITY_TRANSFORM";W[W.LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER]="LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER";
W[W.LATENCY_ACTION_EMBEDS_SET_VIDEO]="LATENCY_ACTION_EMBEDS_SET_VIDEO";W[W.LATENCY_ACTION_SETTINGS]="LATENCY_ACTION_SETTINGS";W[W.LATENCY_ACTION_ABANDONED_STARTUP]="LATENCY_ACTION_ABANDONED_STARTUP";W[W.LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY]="LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY";W[W.LATENCY_ACTION_MEDIA_BROWSER_SEARCH]="LATENCY_ACTION_MEDIA_BROWSER_SEARCH";W[W.LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE]="LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE";W[W.LATENCY_ACTION_WHO_IS_WATCHING]="LATENCY_ACTION_WHO_IS_WATCHING";
W[W.LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH]="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH";W[W.LATENCY_ACTION_LITE_SWITCH_ACCOUNT]="LATENCY_ACTION_LITE_SWITCH_ACCOUNT";W[W.LATENCY_ACTION_ELEMENTS_PERFORMANCE]="LATENCY_ACTION_ELEMENTS_PERFORMANCE";W[W.LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION]="LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION";W[W.LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION]="LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION";W[W.LATENCY_ACTION_OFFLINE_STORE_START]="LATENCY_ACTION_OFFLINE_STORE_START";
W[W.LATENCY_ACTION_REEL_EDITOR]="LATENCY_ACTION_REEL_EDITOR";W[W.LATENCY_ACTION_CHANNEL_SUBSCRIBE]="LATENCY_ACTION_CHANNEL_SUBSCRIBE";W[W.LATENCY_ACTION_CHANNEL_PREVIEW]="LATENCY_ACTION_CHANNEL_PREVIEW";W[W.LATENCY_ACTION_PREFETCH]="LATENCY_ACTION_PREFETCH";W[W.LATENCY_ACTION_ABANDONED_WATCH]="LATENCY_ACTION_ABANDONED_WATCH";W[W.LATENCY_ACTION_LOAD_COMMENT_REPLIES]="LATENCY_ACTION_LOAD_COMMENT_REPLIES";W[W.LATENCY_ACTION_LOAD_COMMENTS]="LATENCY_ACTION_LOAD_COMMENTS";
W[W.LATENCY_ACTION_EDIT_COMMENT]="LATENCY_ACTION_EDIT_COMMENT";W[W.LATENCY_ACTION_NEW_COMMENT]="LATENCY_ACTION_NEW_COMMENT";W[W.LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING]="LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING";W[W.LATENCY_ACTION_EMBED]="LATENCY_ACTION_EMBED";W[W.LATENCY_ACTION_MDX_LAUNCH]="LATENCY_ACTION_MDX_LAUNCH";W[W.LATENCY_ACTION_RESOLVE_URL]="LATENCY_ACTION_RESOLVE_URL";W[W.LATENCY_ACTION_CAST_SPLASH]="LATENCY_ACTION_CAST_SPLASH";W[W.LATENCY_ACTION_MDX_CONNECT_TO_SESSION]="LATENCY_ACTION_MDX_CONNECT_TO_SESSION";
W[W.LATENCY_ACTION_MDX_STREAM_TRANSFER]="LATENCY_ACTION_MDX_STREAM_TRANSFER";W[W.LATENCY_ACTION_MDX_CAST]="LATENCY_ACTION_MDX_CAST";W[W.LATENCY_ACTION_MDX_COMMAND]="LATENCY_ACTION_MDX_COMMAND";W[W.LATENCY_ACTION_MOBILE_LIVE_NAV_MDE]="LATENCY_ACTION_MOBILE_LIVE_NAV_MDE";W[W.LATENCY_ACTION_REEL_SELECT_SEGMENT]="LATENCY_ACTION_REEL_SELECT_SEGMENT";W[W.LATENCY_ACTION_ACCELERATED_EFFECTS]="LATENCY_ACTION_ACCELERATED_EFFECTS";W[W.LATENCY_ACTION_SHORTS_LOAD_PROJECT]="LATENCY_ACTION_SHORTS_LOAD_PROJECT";
W[W.LATENCY_ACTION_SHORTS_TRIM_TO_EDITOR_TRANSCODING]="LATENCY_ACTION_SHORTS_TRIM_TO_EDITOR_TRANSCODING";W[W.LATENCY_ACTION_EDIT_AUDIO_GEN]="LATENCY_ACTION_EDIT_AUDIO_GEN";W[W.LATENCY_ACTION_UPLOAD_AUDIO_MIXER]="LATENCY_ACTION_UPLOAD_AUDIO_MIXER";W[W.LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING]="LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING";W[W.LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING]="LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING";W[W.LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK]="LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK";
W[W.LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD]="LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD";W[W.LATENCY_ACTION_SHORTS_CAMERA_AUDIO_DOWNLOAD]="LATENCY_ACTION_SHORTS_CAMERA_AUDIO_DOWNLOAD";W[W.LATENCY_ACTION_SHORTS_VIDEO_INGESTION]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION";W[W.LATENCY_ACTION_SHORTS_GALLERY]="LATENCY_ACTION_SHORTS_GALLERY";W[W.LATENCY_ACTION_SHORTS_TRIM]="LATENCY_ACTION_SHORTS_TRIM";W[W.LATENCY_ACTION_SHORTS_EDIT]="LATENCY_ACTION_SHORTS_EDIT";W[W.LATENCY_ACTION_SHORTS_CAMERA]="LATENCY_ACTION_SHORTS_CAMERA";
W[W.LATENCY_ACTION_NON_CREATION_MODES_GLOBAL_ENTRYPOINT]="LATENCY_ACTION_NON_CREATION_MODES_GLOBAL_ENTRYPOINT";W[W.LATENCY_ACTION_CREATION_MODES_MODE_SWITCH]="LATENCY_ACTION_CREATION_MODES_MODE_SWITCH";W[W.LATENCY_ACTION_CREATION_MODES_GLOBAL_ENTRYPOINT]="LATENCY_ACTION_CREATION_MODES_GLOBAL_ENTRYPOINT";W[W.LATENCY_ACTION_SWITCH_CAMERA]="LATENCY_ACTION_SWITCH_CAMERA";W[W.LATENCY_ACTION_OPEN_CAMERA]="LATENCY_ACTION_OPEN_CAMERA";W[W.LATENCY_ACTION_MEDIA_ENGINE_DISPLAY_FIRST_FRAME]="LATENCY_ACTION_MEDIA_ENGINE_DISPLAY_FIRST_FRAME";
W[W.LATENCY_ACTION_MEDIA_ENGINE_EXPORT]="LATENCY_ACTION_MEDIA_ENGINE_EXPORT";W[W.LATENCY_ACTION_PRODUCER_IMPORT_LOCAL_MEDIA]="LATENCY_ACTION_PRODUCER_IMPORT_LOCAL_MEDIA";W[W.LATENCY_ACTION_PRODUCER_EXPORT_PROJECT]="LATENCY_ACTION_PRODUCER_EXPORT_PROJECT";W[W.LATENCY_ACTION_PRODUCER_EDITOR]="LATENCY_ACTION_PRODUCER_EDITOR";W[W.LATENCY_ACTION_PARENT_TOOLS_DASHBOARD]="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD";W[W.LATENCY_ACTION_PARENT_TOOLS_COLLECTION]="LATENCY_ACTION_PARENT_TOOLS_COLLECTION";
W[W.LATENCY_ACTION_MUSIC_OFFLINE_PLAYLIST_DETAIL]="LATENCY_ACTION_MUSIC_OFFLINE_PLAYLIST_DETAIL";W[W.LATENCY_ACTION_MUSIC_OFFLINE_ALBUM_DETAIL]="LATENCY_ACTION_MUSIC_OFFLINE_ALBUM_DETAIL";W[W.LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS";W[W.LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS";W[W.LATENCY_ACTION_MUSIC_ALBUM_DETAIL]="LATENCY_ACTION_MUSIC_ALBUM_DETAIL";W[W.LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL]="LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL";
W[W.LATENCY_ACTION_STORE]="LATENCY_ACTION_STORE";W[W.LATENCY_ACTION_CHIPS]="LATENCY_ACTION_CHIPS";W[W.LATENCY_ACTION_SEARCH_ZERO_STATE]="LATENCY_ACTION_SEARCH_ZERO_STATE";W[W.LATENCY_ACTION_LIVE_PAGINATION]="LATENCY_ACTION_LIVE_PAGINATION";W[W.LATENCY_ACTION_LIVE]="LATENCY_ACTION_LIVE";W[W.LATENCY_ACTION_PREBUFFER]="LATENCY_ACTION_PREBUFFER";W[W.LATENCY_ACTION_TENX]="LATENCY_ACTION_TENX";W[W.LATENCY_ACTION_KIDS_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PROFILE_SETTINGS";
W[W.LATENCY_ACTION_KIDS_WATCH_IT_AGAIN]="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN";W[W.LATENCY_ACTION_KIDS_SECRET_CODE]="LATENCY_ACTION_KIDS_SECRET_CODE";W[W.LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS";W[W.LATENCY_ACTION_KIDS_ONBOARDING]="LATENCY_ACTION_KIDS_ONBOARDING";W[W.LATENCY_ACTION_KIDS_VOICE_SEARCH]="LATENCY_ACTION_KIDS_VOICE_SEARCH";W[W.LATENCY_ACTION_KIDS_CURATED_COLLECTION]="LATENCY_ACTION_KIDS_CURATED_COLLECTION";
W[W.LATENCY_ACTION_KIDS_LIBRARY]="LATENCY_ACTION_KIDS_LIBRARY";W[W.LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS";W[W.LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT]="LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT";W[W.LATENCY_ACTION_CREATOR_VIDEO_POLICY]="LATENCY_ACTION_CREATOR_VIDEO_POLICY";W[W.LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION";W[W.LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING";
W[W.LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDIT]="LATENCY_ACTION_CREATOR_VIDEO_EDIT";W[W.LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT";W[W.LATENCY_ACTION_CREATOR_VIDEO_COMMENTS]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS";
W[W.LATENCY_ACTION_CREATOR_VIDEO_CLAIMS]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS";W[W.LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_SONG_ANALYTICS]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_PROMOTION_LIST]="LATENCY_ACTION_CREATOR_PROMOTION_LIST";W[W.LATENCY_ACTION_CREATOR_PROMOTION_EDIT]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT";W[W.LATENCY_ACTION_CREATOR_POST_LIST]="LATENCY_ACTION_CREATOR_POST_LIST";
W[W.LATENCY_ACTION_CREATOR_POST_EDIT]="LATENCY_ACTION_CREATOR_POST_EDIT";W[W.LATENCY_ACTION_CREATOR_POST_COMMENTS]="LATENCY_ACTION_CREATOR_POST_COMMENTS";W[W.LATENCY_ACTION_CREATOR_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_LIVE_STREAMING";W[W.LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT";W[W.LATENCY_ACTION_CREATOR_DIALOG_UPLOADS]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS";W[W.LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES";
W[W.LATENCY_ACTION_CREATOR_CMS_VIDEOS]="LATENCY_ACTION_CREATOR_CMS_VIDEOS";W[W.LATENCY_ACTION_CREATOR_CMS_REPORTS]="LATENCY_ACTION_CREATOR_CMS_REPORTS";W[W.LATENCY_ACTION_CREATOR_CMS_RELEASES]="LATENCY_ACTION_CREATOR_CMS_RELEASES";W[W.LATENCY_ACTION_CREATOR_CMS_POLICIES]="LATENCY_ACTION_CREATOR_CMS_POLICIES";W[W.LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC";W[W.LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING";
W[W.LATENCY_ACTION_CREATOR_CMS_LICENSES]="LATENCY_ACTION_CREATOR_CMS_LICENSES";W[W.LATENCY_ACTION_CREATOR_CMS_ISSUES]="LATENCY_ACTION_CREATOR_CMS_ISSUES";W[W.LATENCY_ACTION_CREATOR_CMS_DASHBOARD]="LATENCY_ACTION_CREATOR_CMS_DASHBOARD";W[W.LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY";W[W.LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS";W[W.LATENCY_ACTION_CREATOR_CMS_CHANNELS]="LATENCY_ACTION_CREATOR_CMS_CHANNELS";
W[W.LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP]="LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP";
W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA]="LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION";
W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS";W[W.LATENCY_ACTION_CREATOR_CMS_ASSETS]="LATENCY_ACTION_CREATOR_CMS_ASSETS";W[W.LATENCY_ACTION_CREATOR_CMS_ART_TRACKS]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS";W[W.LATENCY_ACTION_CREATOR_CMS_ANALYTICS]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_CMS_ALLOWLIST]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST";W[W.LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS";
W[W.LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION";
W[W.LATENCY_ACTION_CREATOR_CHANNEL_EDITING]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING";W[W.LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD]="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD";W[W.LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT";W[W.LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_ARTIST_PROFILE]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE";
W[W.LATENCY_ACTION_CREATOR_ARTIST_CONCERTS]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS";W[W.LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE";W[W.LATENCY_ACTION_EXPERIMENTAL_WATCH_UI]="LATENCY_ACTION_EXPERIMENTAL_WATCH_UI";W[W.LATENCY_ACTION_FINE_SCRUBBING_THUMBNAILS]="LATENCY_ACTION_FINE_SCRUBBING_THUMBNAILS";W[W.LATENCY_ACTION_STORYBOARD_THUMBNAILS]="LATENCY_ACTION_STORYBOARD_THUMBNAILS";
W[W.LATENCY_ACTION_SEARCH_THUMBNAILS]="LATENCY_ACTION_SEARCH_THUMBNAILS";W[W.LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD]="LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD";W[W.LATENCY_ACTION_VOICE_ASSISTANT]="LATENCY_ACTION_VOICE_ASSISTANT";W[W.LATENCY_ACTION_SEARCH_UI]="LATENCY_ACTION_SEARCH_UI";W[W.LATENCY_ACTION_SUGGEST]="LATENCY_ACTION_SUGGEST";W[W.LATENCY_ACTION_AUTO_SEARCH]="LATENCY_ACTION_AUTO_SEARCH";W[W.LATENCY_ACTION_DOWNLOADS]="LATENCY_ACTION_DOWNLOADS";W[W.LATENCY_ACTION_EXPLORE]="LATENCY_ACTION_EXPLORE";
W[W.LATENCY_ACTION_VIDEO_LIST]="LATENCY_ACTION_VIDEO_LIST";W[W.LATENCY_ACTION_HOME_RESUME]="LATENCY_ACTION_HOME_RESUME";W[W.LATENCY_ACTION_SUBSCRIPTIONS_LIST]="LATENCY_ACTION_SUBSCRIPTIONS_LIST";W[W.LATENCY_ACTION_THUMBNAIL_LOAD]="LATENCY_ACTION_THUMBNAIL_LOAD";W[W.LATENCY_ACTION_FIRST_THUMBNAIL_LOAD]="LATENCY_ACTION_FIRST_THUMBNAIL_LOAD";W[W.LATENCY_ACTION_SUBSCRIPTIONS_FEED]="LATENCY_ACTION_SUBSCRIPTIONS_FEED";W[W.LATENCY_ACTION_SUBSCRIPTIONS]="LATENCY_ACTION_SUBSCRIPTIONS";
W[W.LATENCY_ACTION_TRENDING]="LATENCY_ACTION_TRENDING";W[W.LATENCY_ACTION_LIBRARY]="LATENCY_ACTION_LIBRARY";W[W.LATENCY_ACTION_VIDEO_THUMBNAIL]="LATENCY_ACTION_VIDEO_THUMBNAIL";W[W.LATENCY_ACTION_SHOW_MORE]="LATENCY_ACTION_SHOW_MORE";W[W.LATENCY_ACTION_VIDEO_PREVIEW]="LATENCY_ACTION_VIDEO_PREVIEW";W[W.LATENCY_ACTION_AD_TO_AD]="LATENCY_ACTION_AD_TO_AD";W[W.LATENCY_ACTION_VIDEO_TO_AD]="LATENCY_ACTION_VIDEO_TO_AD";W[W.LATENCY_ACTION_AD_TO_VIDEO]="LATENCY_ACTION_AD_TO_VIDEO";
W[W.LATENCY_ACTION_DIRECT_PLAYBACK]="LATENCY_ACTION_DIRECT_PLAYBACK";W[W.LATENCY_ACTION_PREBUFFER_VIDEO]="LATENCY_ACTION_PREBUFFER_VIDEO";W[W.LATENCY_ACTION_PREFETCH_VIDEO]="LATENCY_ACTION_PREFETCH_VIDEO";W[W.LATENCY_ACTION_STARTUP]="LATENCY_ACTION_STARTUP";W[W.LATENCY_ACTION_INLINE_TO_WATCH]="LATENCY_ACTION_INLINE_TO_WATCH";W[W.LATENCY_ACTION_MUSIC_IMMERSIVE_WATCH]="LATENCY_ACTION_MUSIC_IMMERSIVE_WATCH";W[W.LATENCY_ACTION_ONBOARDING]="LATENCY_ACTION_ONBOARDING";W[W.LATENCY_ACTION_LOGIN]="LATENCY_ACTION_LOGIN";
W[W.LATENCY_ACTION_REEL_WATCH]="LATENCY_ACTION_REEL_WATCH";W[W.LATENCY_ACTION_WATCH]="LATENCY_ACTION_WATCH";W[W.LATENCY_ACTION_RESULTS]="LATENCY_ACTION_RESULTS";W[W.LATENCY_ACTION_CHANNELS]="LATENCY_ACTION_CHANNELS";W[W.LATENCY_ACTION_HOME]="LATENCY_ACTION_HOME";W[W.LATENCY_ACTION_BROWSE]="LATENCY_ACTION_BROWSE";W[W.LATENCY_ACTION_USER_ACTION]="LATENCY_ACTION_USER_ACTION";W[W.LATENCY_ACTION_INFRASTRUCTURE]="LATENCY_ACTION_INFRASTRUCTURE";W[W.LATENCY_ACTION_PAGE_NAVIGATION]="LATENCY_ACTION_PAGE_NAVIGATION";
W[W.LATENCY_ACTION_UNKNOWN]="LATENCY_ACTION_UNKNOWN";var Zu={LATENCY_NETWORK_MOBILE:2,LATENCY_NETWORK_WIFI:1,LATENCY_NETWORK_UNKNOWN:0};Zu[Zu.LATENCY_NETWORK_MOBILE]="LATENCY_NETWORK_MOBILE";Zu[Zu.LATENCY_NETWORK_WIFI]="LATENCY_NETWORK_WIFI";Zu[Zu.LATENCY_NETWORK_UNKNOWN]="LATENCY_NETWORK_UNKNOWN";
var X={CONN_INVALID:31,CONN_CELLULAR_5G_NSA:12,CONN_CELLULAR_5G_SA:11,CONN_WIFI_METERED:10,CONN_CELLULAR_5G:9,CONN_DISCO:8,CONN_CELLULAR_UNKNOWN:7,CONN_CELLULAR_4G:6,CONN_CELLULAR_3G:5,CONN_CELLULAR_2G:4,CONN_WIFI:3,CONN_NONE:2,CONN_UNKNOWN:1,CONN_DEFAULT:0};X[X.CONN_INVALID]="CONN_INVALID";X[X.CONN_CELLULAR_5G_NSA]="CONN_CELLULAR_5G_NSA";X[X.CONN_CELLULAR_5G_SA]="CONN_CELLULAR_5G_SA";X[X.CONN_WIFI_METERED]="CONN_WIFI_METERED";X[X.CONN_CELLULAR_5G]="CONN_CELLULAR_5G";X[X.CONN_DISCO]="CONN_DISCO";
X[X.CONN_CELLULAR_UNKNOWN]="CONN_CELLULAR_UNKNOWN";X[X.CONN_CELLULAR_4G]="CONN_CELLULAR_4G";X[X.CONN_CELLULAR_3G]="CONN_CELLULAR_3G";X[X.CONN_CELLULAR_2G]="CONN_CELLULAR_2G";X[X.CONN_WIFI]="CONN_WIFI";X[X.CONN_NONE]="CONN_NONE";X[X.CONN_UNKNOWN]="CONN_UNKNOWN";X[X.CONN_DEFAULT]="CONN_DEFAULT";
var Y={DETAILED_NETWORK_TYPE_NR_NSA:126,DETAILED_NETWORK_TYPE_NR_SA:125,DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED:124,DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT:123,DETAILED_NETWORK_TYPE_DISCONNECTED:122,DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN:121,DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN:120,DETAILED_NETWORK_TYPE_WIMAX:119,DETAILED_NETWORK_TYPE_ETHERNET:118,DETAILED_NETWORK_TYPE_BLUETOOTH:117,DETAILED_NETWORK_TYPE_WIFI:116,DETAILED_NETWORK_TYPE_LTE:115,DETAILED_NETWORK_TYPE_HSPAP:114,DETAILED_NETWORK_TYPE_EHRPD:113,
DETAILED_NETWORK_TYPE_EVDO_B:112,DETAILED_NETWORK_TYPE_UMTS:111,DETAILED_NETWORK_TYPE_IDEN:110,DETAILED_NETWORK_TYPE_HSUPA:109,DETAILED_NETWORK_TYPE_HSPA:108,DETAILED_NETWORK_TYPE_HSDPA:107,DETAILED_NETWORK_TYPE_EVDO_A:106,DETAILED_NETWORK_TYPE_EVDO_0:105,DETAILED_NETWORK_TYPE_CDMA:104,DETAILED_NETWORK_TYPE_1_X_RTT:103,DETAILED_NETWORK_TYPE_GPRS:102,DETAILED_NETWORK_TYPE_EDGE:101,DETAILED_NETWORK_TYPE_UNKNOWN:0};Y[Y.DETAILED_NETWORK_TYPE_NR_NSA]="DETAILED_NETWORK_TYPE_NR_NSA";
Y[Y.DETAILED_NETWORK_TYPE_NR_SA]="DETAILED_NETWORK_TYPE_NR_SA";Y[Y.DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED]="DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED";Y[Y.DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT]="DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT";Y[Y.DETAILED_NETWORK_TYPE_DISCONNECTED]="DETAILED_NETWORK_TYPE_DISCONNECTED";Y[Y.DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN";Y[Y.DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN";
Y[Y.DETAILED_NETWORK_TYPE_WIMAX]="DETAILED_NETWORK_TYPE_WIMAX";Y[Y.DETAILED_NETWORK_TYPE_ETHERNET]="DETAILED_NETWORK_TYPE_ETHERNET";Y[Y.DETAILED_NETWORK_TYPE_BLUETOOTH]="DETAILED_NETWORK_TYPE_BLUETOOTH";Y[Y.DETAILED_NETWORK_TYPE_WIFI]="DETAILED_NETWORK_TYPE_WIFI";Y[Y.DETAILED_NETWORK_TYPE_LTE]="DETAILED_NETWORK_TYPE_LTE";Y[Y.DETAILED_NETWORK_TYPE_HSPAP]="DETAILED_NETWORK_TYPE_HSPAP";Y[Y.DETAILED_NETWORK_TYPE_EHRPD]="DETAILED_NETWORK_TYPE_EHRPD";Y[Y.DETAILED_NETWORK_TYPE_EVDO_B]="DETAILED_NETWORK_TYPE_EVDO_B";
Y[Y.DETAILED_NETWORK_TYPE_UMTS]="DETAILED_NETWORK_TYPE_UMTS";Y[Y.DETAILED_NETWORK_TYPE_IDEN]="DETAILED_NETWORK_TYPE_IDEN";Y[Y.DETAILED_NETWORK_TYPE_HSUPA]="DETAILED_NETWORK_TYPE_HSUPA";Y[Y.DETAILED_NETWORK_TYPE_HSPA]="DETAILED_NETWORK_TYPE_HSPA";Y[Y.DETAILED_NETWORK_TYPE_HSDPA]="DETAILED_NETWORK_TYPE_HSDPA";Y[Y.DETAILED_NETWORK_TYPE_EVDO_A]="DETAILED_NETWORK_TYPE_EVDO_A";Y[Y.DETAILED_NETWORK_TYPE_EVDO_0]="DETAILED_NETWORK_TYPE_EVDO_0";Y[Y.DETAILED_NETWORK_TYPE_CDMA]="DETAILED_NETWORK_TYPE_CDMA";
Y[Y.DETAILED_NETWORK_TYPE_1_X_RTT]="DETAILED_NETWORK_TYPE_1_X_RTT";Y[Y.DETAILED_NETWORK_TYPE_GPRS]="DETAILED_NETWORK_TYPE_GPRS";Y[Y.DETAILED_NETWORK_TYPE_EDGE]="DETAILED_NETWORK_TYPE_EDGE";Y[Y.DETAILED_NETWORK_TYPE_UNKNOWN]="DETAILED_NETWORK_TYPE_UNKNOWN";var $u={LATENCY_PLAYER_RTSP:7,LATENCY_PLAYER_HTML5_INLINE:6,LATENCY_PLAYER_HTML5_FULLSCREEN:5,LATENCY_PLAYER_HTML5:4,LATENCY_PLAYER_FRAMEWORK:3,LATENCY_PLAYER_FLASH:2,LATENCY_PLAYER_EXO:1,LATENCY_PLAYER_UNKNOWN:0};$u[$u.LATENCY_PLAYER_RTSP]="LATENCY_PLAYER_RTSP";
$u[$u.LATENCY_PLAYER_HTML5_INLINE]="LATENCY_PLAYER_HTML5_INLINE";$u[$u.LATENCY_PLAYER_HTML5_FULLSCREEN]="LATENCY_PLAYER_HTML5_FULLSCREEN";$u[$u.LATENCY_PLAYER_HTML5]="LATENCY_PLAYER_HTML5";$u[$u.LATENCY_PLAYER_FRAMEWORK]="LATENCY_PLAYER_FRAMEWORK";$u[$u.LATENCY_PLAYER_FLASH]="LATENCY_PLAYER_FLASH";$u[$u.LATENCY_PLAYER_EXO]="LATENCY_PLAYER_EXO";$u[$u.LATENCY_PLAYER_UNKNOWN]="LATENCY_PLAYER_UNKNOWN";
var av={LATENCY_AD_BREAK_TYPE_POSTROLL:3,LATENCY_AD_BREAK_TYPE_MIDROLL:2,LATENCY_AD_BREAK_TYPE_PREROLL:1,LATENCY_AD_BREAK_TYPE_UNKNOWN:0};av[av.LATENCY_AD_BREAK_TYPE_POSTROLL]="LATENCY_AD_BREAK_TYPE_POSTROLL";av[av.LATENCY_AD_BREAK_TYPE_MIDROLL]="LATENCY_AD_BREAK_TYPE_MIDROLL";av[av.LATENCY_AD_BREAK_TYPE_PREROLL]="LATENCY_AD_BREAK_TYPE_PREROLL";av[av.LATENCY_AD_BREAK_TYPE_UNKNOWN]="LATENCY_AD_BREAK_TYPE_UNKNOWN";var bv={LATENCY_ACTION_ERROR_STARTUP_TIMEOUT:1,LATENCY_ACTION_ERROR_UNSPECIFIED:0};
bv[bv.LATENCY_ACTION_ERROR_STARTUP_TIMEOUT]="LATENCY_ACTION_ERROR_STARTUP_TIMEOUT";bv[bv.LATENCY_ACTION_ERROR_UNSPECIFIED]="LATENCY_ACTION_ERROR_UNSPECIFIED";var cv={LIVE_STREAM_MODE_WINDOW:5,LIVE_STREAM_MODE_POST:4,LIVE_STREAM_MODE_LP:3,LIVE_STREAM_MODE_LIVE:2,LIVE_STREAM_MODE_DVR:1,LIVE_STREAM_MODE_UNKNOWN:0};cv[cv.LIVE_STREAM_MODE_WINDOW]="LIVE_STREAM_MODE_WINDOW";cv[cv.LIVE_STREAM_MODE_POST]="LIVE_STREAM_MODE_POST";cv[cv.LIVE_STREAM_MODE_LP]="LIVE_STREAM_MODE_LP";
cv[cv.LIVE_STREAM_MODE_LIVE]="LIVE_STREAM_MODE_LIVE";cv[cv.LIVE_STREAM_MODE_DVR]="LIVE_STREAM_MODE_DVR";cv[cv.LIVE_STREAM_MODE_UNKNOWN]="LIVE_STREAM_MODE_UNKNOWN";var dv={VIDEO_STREAM_TYPE_VOD:3,VIDEO_STREAM_TYPE_DVR:2,VIDEO_STREAM_TYPE_LIVE:1,VIDEO_STREAM_TYPE_UNSPECIFIED:0};dv[dv.VIDEO_STREAM_TYPE_VOD]="VIDEO_STREAM_TYPE_VOD";dv[dv.VIDEO_STREAM_TYPE_DVR]="VIDEO_STREAM_TYPE_DVR";dv[dv.VIDEO_STREAM_TYPE_LIVE]="VIDEO_STREAM_TYPE_LIVE";dv[dv.VIDEO_STREAM_TYPE_UNSPECIFIED]="VIDEO_STREAM_TYPE_UNSPECIFIED";
var ev={YT_IDB_TRANSACTION_TYPE_READ:2,YT_IDB_TRANSACTION_TYPE_WRITE:1,YT_IDB_TRANSACTION_TYPE_UNKNOWN:0};ev[ev.YT_IDB_TRANSACTION_TYPE_READ]="YT_IDB_TRANSACTION_TYPE_READ";ev[ev.YT_IDB_TRANSACTION_TYPE_WRITE]="YT_IDB_TRANSACTION_TYPE_WRITE";ev[ev.YT_IDB_TRANSACTION_TYPE_UNKNOWN]="YT_IDB_TRANSACTION_TYPE_UNKNOWN";var fv={PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN:2,PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT:1,PLAYER_ROTATION_TYPE_UNKNOWN:0};fv[fv.PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN]="PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN";
fv[fv.PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT]="PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT";fv[fv.PLAYER_ROTATION_TYPE_UNKNOWN]="PLAYER_ROTATION_TYPE_UNKNOWN";var gv="actionVisualElement spinnerInfo cacheAttempts resourceInfo playerInfo commentInfo mdxInfo watchInfo thumbnailLoadInfo creatorInfo unpluggedInfo reelInfo subscriptionsFeedInfo requestIds mediaBrowserActionInfo musicLoadActionInfo shoppingInfo webViewInfo prefetchInfo accelerationSession commerceInfo inlineToWatchInfo mediaEngineMetadata miniAppInfo webInfo tvInfo kabukiInfo mwebInfo musicInfo transcodingContext creationModesContext cameraMetadata producerMediaAssetMetadata".split(" ");function hv(a,b){Jp.call(this,1,arguments);this.timer=b}
v(hv,Jp);var iv=new Kp;var jv=x.ytLoggingLatencyUsageStats_||{};A("ytLoggingLatencyUsageStats_",jv);function kv(){this.h=0}
function lv(){kv.h||(kv.h=new kv);return kv.h}
kv.prototype.tick=function(a,b,c,d){mv(this,"tick_"+a+"_"+b)||(c={timestamp:c,cttAuthInfo:d},R("web_csi_via_jspb")?(d=new zl,F(d,1,a),F(d,2,b),a=R("jspb_sparse_encoded_pivot")?new Cl([{}]):new Cl,ce(a,zl,5,Dl,d),pt(a,c)):Mn("latencyActionTicked",{tickName:a,clientActionNonce:b},c))};
kv.prototype.info=function(a,b,c){var d=Object.keys(a).join("");mv(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,Mn("latencyActionInfo",a,{cttAuthInfo:c}))};
kv.prototype.jspbInfo=function(a,b,c){for(var d="",e=0;e<a.toJSON().length;e++)void 0!==a.toJSON()[e]&&(d=0===e?d.concat(""+e):d.concat("_"+e));mv(this,"info_"+d+"_"+b)||(F(a,2,b),b={cttAuthInfo:c},c=R("jspb_sparse_encoded_pivot")?new Cl([{}]):new Cl,ce(c,xl,7,Dl,a),pt(c,b))};
kv.prototype.span=function(a,b,c){var d=Object.keys(a).join("");mv(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,Mn("latencyActionSpan",a,{cttAuthInfo:c}))};
function mv(a,b){jv[b]=jv[b]||{count:0};var c=jv[b];c.count++;c.time=S();a.h||(a.h=yn(function(){var d=S(),e;for(e in jv)jv[e]&&6E4<d-jv[e].time&&delete jv[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new un("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||xt(c)),!0):!1}
;var nv=window;function ov(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function pv(){var a;if(R("csi_use_performance_navigation_timing")||R("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==qv?void 0:null==(a=qv.getEntriesByType)?void 0:null==(b=a.call(qv,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=rv(e.requestStart),e.responseEnd=rv(e.responseEnd),e.redirectStart=rv(e.redirectStart),e.redirectEnd=rv(e.redirectEnd),e.domainLookupEnd=rv(e.domainLookupEnd),e.connectStart=rv(e.connectStart),e.connectEnd=
rv(e.connectEnd),e.responseStart=rv(e.responseStart),e.secureConnectionStart=rv(e.secureConnectionStart),e.domainLookupStart=rv(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=qv.timing}else a=qv.timing;return a}
function rv(a){return Math.round(sv()+a)}
function sv(){return(R("csi_use_time_origin")||R("csi_use_time_origin_tvhtml5"))&&qv.timeOrigin?Math.floor(qv.timeOrigin):qv.timing.navigationStart}
var qv=nv.performance||nv.mozPerformance||nv.msPerformance||nv.webkitPerformance||new ov;var tv=!1,uv={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Ya(qv.clearResourceTimings||qv.webkitClearResourceTimings||qv.mozClearResourceTimings||qv.msClearResourceTimings||qv.oClearResourceTimings||db,qv);function vv(a,b,c,d){if(null!==b){if("yt_lt"===a){var e="string"===typeof b?b:""+b;Ku(c).loadType=e}(a=Yu(a,b,c))&&wv(a,c,d)}}
function wv(a,b,c){if(!R("web_csi_via_jspb")||(void 0===c?0:c))c=Qu(b||""),Du(c.info,a),a.loadType&&(c=a.loadType,Ku(b).loadType=c),Du(Nu(b),a),c=Ou(b),b=Iu(b).cttAuthInfo,lv().info(a,c,b);else{c=new xl;var d=Object.keys(a);a=Object.values(a);for(var e=0;e<d.length;e++){var f=d[e];try{switch(f){case "actionType":F(c,1,W[a[e]]);break;case "clientActionNonce":F(c,2,a[e]);break;case "clientScreenNonce":F(c,4,a[e]);break;case "loadType":F(c,3,a[e]);break;case "isPrewarmedLaunch":F(c,92,a[e]);break;case "isFirstInstall":F(c,
55,a[e]);break;case "networkType":F(c,5,Zu[a[e]]);break;case "connectionType":F(c,26,X[a[e]]);break;case "detailedConnectionType":F(c,27,Y[a[e]]);break;case "isVisible":F(c,6,a[e]);break;case "playerType":F(c,7,$u[a[e]]);break;case "clientPlaybackNonce":F(c,8,a[e]);break;case "adClientPlaybackNonce":F(c,28,a[e]);break;case "previousCpn":F(c,77,a[e]);break;case "targetCpn":F(c,76,a[e]);break;case "isMonetized":F(c,9,a[e]);break;case "isPrerollAllowed":F(c,16,a[e]);break;case "isPrerollShown":F(c,17,
a[e]);break;case "adType":F(c,12,a[e]);break;case "adTypesAllowed":F(c,36,a[e]);break;case "adNetworks":F(c,37,a[e]);break;case "previousAction":F(c,13,W[a[e]]);break;case "isRedSubscriber":F(c,14,a[e]);break;case "serverTimeMs":fe(c,15,a[e]);break;case "videoId":c.setVideoId(a[e]);break;case "adVideoId":F(c,20,a[e]);break;case "targetVideoId":F(c,78,a[e]);break;case "adBreakType":F(c,21,av[a[e]]);break;case "isNavigation":F(c,25,a[e]);break;case "viewportHeight":fe(c,29,a[e]);break;case "viewportWidth":fe(c,
30,a[e]);break;case "screenHeight":fe(c,84,a[e]);break;case "screenWidth":fe(c,85,a[e]);break;case "browseId":F(c,31,a[e]);break;case "isCacheHit":F(c,32,a[e]);break;case "httpProtocol":F(c,33,a[e]);break;case "transportProtocol":F(c,34,a[e]);break;case "searchQuery":F(c,41,a[e]);break;case "isContinuation":F(c,42,a[e]);break;case "availableProcessors":fe(c,43,a[e]);break;case "sdk":F(c,44,a[e]);break;case "isLocalStream":F(c,45,a[e]);break;case "navigationRequestedSameUrl":F(c,64,a[e]);break;case "shellStartupDurationMs":fe(c,
70,a[e]);break;case "appInstallDataAgeMs":fe(c,73,a[e]);break;case "latencyActionError":F(c,71,bv[a[e]]);break;case "actionStep":fe(c,79,a[e]);break;case "jsHeapSizeLimit":F(c,80,a[e]);break;case "totalJsHeapSize":F(c,81,a[e]);break;case "usedJsHeapSize":F(c,82,a[e]);break;case "sourceVideoDurationMs":F(c,90,a[e]);break;case "videoOutputFrames":F(c,93,a[e]);break;case "isResume":F(c,104,a[e]);break;case "debugTicksExcluded":F(c,105,a[e]);break;case "abandonedPing":F(c,113,a[e]);break;case "adPrebufferedTimeSecs":fe(c,
39,a[e]);break;case "isLivestream":F(c,47,a[e]);break;case "liveStreamMode":F(c,91,cv[a[e]]);break;case "adCpn2":F(c,48,a[e]);break;case "adDaiDriftMillis":F(c,49,a[e]);break;case "videoStreamType":F(c,53,dv[a[e]]);break;case "playbackRequiresTap":F(c,56,a[e]);break;case "performanceNavigationTiming":F(c,67,a[e]);break;case "transactionType":F(c,74,ev[a[e]]);break;case "playerRotationType":F(c,101,fv[a[e]]);break;case "allowedPreroll":F(c,10,a[e]);break;case "shownPreroll":F(c,11,a[e]);break;case "getHomeRequestId":F(c,
57,a[e]);break;case "getSearchRequestId":F(c,60,a[e]);break;case "getPlayerRequestId":F(c,61,a[e]);break;case "getWatchNextRequestId":F(c,62,a[e]);break;case "getBrowseRequestId":F(c,63,a[e]);break;case "getLibraryRequestId":F(c,66,a[e]);break;case "isTransformerEnabledForFeature":F(c,106,a[e]);break;case "sourceVideoFrameCount":F(c,109,a[e]);break;default:gv.includes(f)&&$l(new un("Codegen laipb translator asked to translate message field",""+f))}}catch(g){$l(Error("Codegen laipb translator failed to set "+
f))}}xv(c,b)}}
function xv(a,b){var c=je(a,3);c&&(Ku(b).loadType=c);Qu(b||"").jspbInfo.push(a);c=Ou(b);b=Iu(b).cttAuthInfo;lv().jspbInfo(a,c,b)}
function yv(a,b,c){if(!b&&"_"!==a[0]){var d=a;qv.mark&&(0==d.lastIndexOf("mark_",0)||(d="mark_"+d),c&&(d+=" ("+c+")"),qv.mark(d))}d=Qu(c||"");d.tick[a]=b||S();if(d.callback&&d.callback[a]){d=t(d.callback[a]);for(var e=d.next();!e.done;e=d.next())e=e.value,e()}d=Mu(c);d.gelTicks&&(d.gelTicks[a]=!0);e=Lu(c);d=b||S();R("log_repeated_ytcsi_ticks")?a in e||(e[a]=d):e[a]=d;e=Ou(c);var f=Iu(c).cttAuthInfo;"_start"===a?(a=lv(),mv(a,"baseline_"+e)||(b={timestamp:b,cttAuthInfo:f},R("web_csi_via_jspb")?(a=new sl,
F(a,1,e),e=R("jspb_sparse_encoded_pivot")?new Cl([{}]):new Cl,ce(e,sl,6,Dl,a),pt(e,b)):Mn("latencyActionBaselined",{clientActionNonce:e},b))):lv().tick(a,e,b,f);zv(c);return d}
function Av(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=Gr+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Bv(a){var b=pv(),c=sv(),d=O("CSI_START_TIMESTAMP_MILLIS",0);0<d&&!R("embeds_web_enable_csi_start_override_killswitch")&&(c=d);c&&(yv("srt",b.responseStart),1!==a.prerender&&yv("_start",c,void 0));a=Cv();0<a&&yv("fpt",a);a=pv();a.isPerformanceNavigationTiming&&wv({performanceNavigationTiming:!0});yv("nreqs",a.requestStart,void 0);yv("nress",a.responseStart,void 0);yv("nrese",a.responseEnd,void 0);0<a.redirectEnd-a.redirectStart&&(yv("nrs",a.redirectStart,void 0),yv("nre",a.redirectEnd,void 0));
0<a.domainLookupEnd-a.domainLookupStart&&(yv("ndnss",a.domainLookupStart,void 0),yv("ndnse",a.domainLookupEnd,void 0));0<a.connectEnd-a.connectStart&&(yv("ntcps",a.connectStart,void 0),yv("ntcpe",a.connectEnd,void 0));a.secureConnectionStart>=sv()&&0<a.connectEnd-a.secureConnectionStart&&(yv("nstcps",a.secureConnectionStart,void 0),yv("ntcpe",a.connectEnd,void 0));qv&&"getEntriesByType"in qv&&Dv()}
function Ev(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);rc()&&a.setAttribute("nonce",rc());return c?(a=qv.getEntriesByName(c))&&a[0]&&(a=a[0],c=sv(),yv("rsf_"+b,c+Math.round(a.fetchStart)),yv("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function Fv(){var a=[];if(document.querySelector&&qv&&qv.getEntriesByName)for(var b in uv)if(uv.hasOwnProperty(b)){var c=uv[b];Ev(b,c)&&a.push(c)}return a}
function Dv(){var a=window.location.protocol,b=qv.getEntriesByType("resource");b=hb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=ib(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(yv("wffs",rv(b.startTime)),yv("wffe",rv(b.responseEnd)))}
function Gv(a){var b=Hv("aft",a);if(b)return b;b=O((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=Hv(b[d],a);if(e)return e}return NaN}
function Hv(a,b){if(a=Lu(b)[a])return"number"===typeof a?a:a[a.length-1]}
function zv(a){var b=Hv("_start",a),c=Gv(a);b&&c&&!tv&&(Mp(iv,new hv(Math.round(c-b),a)),tv=!0)}
function Iv(a,b){for(var c=t(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!Iv(a[d],b[d]))return!1;return!0}
function Cv(){if(qv.getEntriesByType){var a=qv.getEntriesByType("paint");if(a=jb(a,function(b){return"first-paint"===b.name}))return rv(a.startTime)}a=qv.timing;
return a.ye?Math.max(0,a.ye):0}
;function Jv(a,b){Zl(function(){Qu("").info.actionType=a;b&&Vl("TIMING_AFT_KEYS",b);Vl("TIMING_ACTION",a);if(R("web_csi_via_jspb")){var c=O("TIMING_INFO",{}),d=new xl;c=t(Object.entries(c));for(var e=c.next();!e.done;e=c.next()){var f=t(e.value);e=f.next().value;f=f.next().value;switch(e){case "GetBrowse_rid":yl(d,vl(ul(e),String(f)));break;case "GetGuide_rid":yl(d,vl(ul(e),String(f)));break;case "GetHome_rid":yl(d,vl(ul(e),String(f)));break;case "GetPlayer_rid":yl(d,vl(ul(e),String(f)));break;case "GetSearch_rid":yl(d,
vl(ul(e),String(f)));break;case "GetSettings_rid":yl(d,vl(ul(e),String(f)));break;case "GetTrending_rid":yl(d,vl(ul(e),String(f)));break;case "GetWatchNext_rid":yl(d,vl(ul(e),String(f)));break;case "yt_red":F(d,14,!!f);break;case "yt_ad":F(d,9,!!f)}}xv(d);d=new xl;d=F(d,25,!0);d=F(d,1,W[Xu(O("TIMING_ACTION"))]);(c=O("PREVIOUS_ACTION"))&&F(d,13,W[Xu(c)]);(c=O("CLIENT_PROTOCOL"))&&F(d,33,c);(c=O("CLIENT_TRANSPORT"))&&F(d,34,c);(c=Nt())&&"UNDEFINED_CSN"!==c&&F(d,4,c);c=Av();1!==c&&-1!==c||F(d,6,!0);
c=Ju();Ku();F(d,3,"cold");Bv(c);c=Fv();if(0<c.length)for(c=t(c),e=c.next();!e.done;e=c.next())e=e.value,f=new wl,F(f,1,e),ee(d,83,wl,f);xv(d)}else{d=O("TIMING_INFO",{});for(c in d)d.hasOwnProperty(c)&&vv(c,d[c]);d={isNavigation:!0,actionType:Xu(O("TIMING_ACTION"))};if(c=O("PREVIOUS_ACTION"))d.previousAction=Xu(c);if(c=O("CLIENT_PROTOCOL"))d.httpProtocol=c;if(c=O("CLIENT_TRANSPORT"))d.transportProtocol=c;(c=Nt())&&"UNDEFINED_CSN"!==c&&(d.clientScreenNonce=c);c=Av();if(1===c||-1===c)d.isVisible=!0;
Ku();Ju();d.loadType="cold";Bv(Ju());c=Fv();if(0<c.length)for(d.resourceInfo=[],c=t(c),e=c.next();!e.done;e=c.next())d.resourceInfo.push({resourceCache:e.value});wv(d)}d=Ju();c=Nu();if("cold"===Ku().loadType&&("cold"===d.yt_lt||"cold"===c.loadType)){e=Lu();f=Mu();f=f.gelTicks?f.gelTicks:f.gelTicks={};for(var g in e)if(!(g in f))if("number"===typeof e[g])yv(g,Hv(g));else if(R("log_repeated_ytcsi_ticks"))for(var h=t(e[g]),l=h.next();!l.done;l=h.next())l=l.value,yv(g.slice(1),l);g={};e=!1;f=t(Object.keys(d));
for(h=f.next();!h.done;h=f.next())h=h.value,(h=Yu(h,d[h]))&&!Iv(Nu(),h)&&(Du(c,h),Du(g,h),e=!0);e&&wv(g)}A("ytglobal.timingready_",!0);g=O("TIMING_ACTION");B("ytglobal.timingready_")&&g&&Kv()&&Gv()&&zv()})()}
function Lv(a,b,c,d){Zl(vv)(a,b,c,d)}
function Mv(a,b,c){return Zl(yv)(a,b,c)}
function Kv(){return Zl(function(){return"_start"in Lu()})()}
function Nv(){Zl(function(){var a=Ou();requestAnimationFrame(function(){setTimeout(function(){a===Ou()&&Mv("ol",void 0,void 0)},0)})})()}
var Ov=window;Ov.ytcsi&&(Ov.ytcsi.info=Lv,Ov.ytcsi.tick=Mv);var Pv="tokens consistency mss client_location entities adblock_detection response_received_commands store PLAYER_PRELOAD".split(" "),Qv=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse"];function Rv(a,b,c,d){this.j=a;this.X=b;this.m=c;this.l=d;this.i=void 0;this.h=new Map;a.jb||(a.jb={});a.jb=Object.assign({},Cu,a.jb)}
function Sv(a,b,c,d){if(void 0!==Rv.h){if(d=Rv.h,a=[a!==d.j,b!==d.X,c!==d.m,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new un("InnerTubeTransportService is already initialized",a);
}else Rv.h=new Rv(a,b,c,d)}
function Tv(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?Zm:c;var d=uu(b,a.j);if(!d)return Mf(new un("Error: No request builder found for command.",b));var e=d.m(b,void 0,c);return e?new Gf(function(f){var g,h,l;return w(function(m){if(1==m.h){h="cors"===(null==(g=e.hb)?void 0:g.mode)?"cors":void 0;if(a.m.Ve){var p=e.config,r;p=null==p?void 0:null==(r=p.Vb)?void 0:r.sessionIndex;r=Ym(0,{sessionIndex:p});l=Object.assign({},Uv(h),r);return m.A(2)}return m.yield(Vv(e.config,
h),3)}2!=m.h&&(l=m.i);f(Wv(a,e,l));m.h=0})}):Mf(new un("Error: Failed to build request for command.",b))}
function Xv(a,b,c){var d;if(b&&!(null==b?0:null==(d=b.Nf)?0:d.Rf)&&a.l){d=t(Pv);for(var e=d.next();!e.done;e=d.next())e=e.value,a.l[e]&&a.l[e].handleResponse(b,c)}}
function Wv(a,b,c){var d,e,f,g,h,l,m,p,r,y,u,z,D,G,M,P,T,da,Z,na,La,ya,za,va,ma,L,jf,Uc,kf;return w(function(ja){switch(ja.h){case 1:ja.A(2);break;case 3:if((d=ja.i)&&!d.isExpired())return ja.return(Promise.resolve(d.h()));case 2:if(!(null==(e=b)?0:null==(f=e.Oa)?0:f.context)){ja.A(4);break}g=b.Oa.context;if(!R("web_async_context_processor")){h=t([]);for(l=h.next();!l.done;l=h.next())m=l.value,m.Kf(g);ja.A(4);break}return ja.yield([].reduce(function(lf,xh){return lf.then(function(){return xh.Jf(g)})},
Promise.resolve()),4);
case 4:if(null==(p=a.i)||!p.Of(b.input,b.Oa)){ja.A(7);break}return ja.yield(a.i.Gf(b.input,b.Oa),8);case 8:return r=ja.i,R("kevlar_process_local_innertube_responses_killswitch")||Xv(a,r,b),ja.return(r);case 7:return(z=null==(u=b.config)?void 0:u.Ia)&&a.h.has(z)&&R("web_memoize_inflight_requests")?y=a.h.get(z):(D=JSON.stringify(b.Oa),P=null!=(M=null==(G=b.hb)?void 0:G.headers)?M:{},b.hb=Object.assign({},b.hb,{headers:Object.assign({},P,c)}),T=Object.assign({},b.hb),"POST"===b.hb.method&&(T=Object.assign({},
T,{body:D})),(null==(da=b.config)?0:da.Fe)&&Mv(b.config.Fe),Z=function(){return a.X.fetch(b.input,T,b.config)},y=Z(),z&&a.h.set(z,y)),ja.yield(y,9);
case 9:if((na=ja.i)&&"error"in na&&(null==(La=na)?0:null==(ya=La.error)?0:ya.details))for(za=na.error.details,va=t(za),ma=va.next();!ma.done;ma=va.next())L=ma.value,(jf=L["@type"])&&-1<Qv.indexOf(jf)&&(delete L["@type"],na=L);z&&a.h.has(z)&&a.h.delete(z);(null==(Uc=b.config)?0:Uc.Ge)&&Mv(b.config.Ge);if(na||null==(kf=a.i)||!kf.Af(b.input,b.Oa)){ja.A(10);break}return ja.yield(a.i.Ff(b.input,b.Oa),11);case 11:na=ja.i;case 10:return Xv(a,na,b),ja.return(na||void 0)}})}
function Vv(a,b){var c,d,e,f;return w(function(g){if(1==g.h){e=null==(c=a)?void 0:null==(d=c.Vb)?void 0:d.sessionIndex;var h=g.yield;var l=Lf(Ym(0,{sessionIndex:e}));return h.call(g,l,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},Uv(b),f)))})}
function Uv(a){var b={"Content-Type":"application/json"};O("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=O("EOM_VISITOR_DATA"):O("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=O("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=O("LOGGED_IN",!1);"cors"!==a&&((a=O("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=O("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=O("CHROME_CONNECTED_HEADER"))&&(b["X-Youtube-Chrome-Connected"]=a),(a=O("DOMAIN_ADMIN_STATE"))&&
(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var Yv=new hs("INNERTUBE_TRANSPORT_TOKEN");var Zv=["share/get_web_player_share_panel"],$v=["feedback"],aw=["notification/modify_channel_preference"],bw=["browse/edit_playlist"],cw=["subscription/subscribe"],dw=["subscription/unsubscribe"];function ew(){}
v(ew,zu);ew.prototype.j=function(){return cw};
ew.prototype.h=function(a){return ts(a,Ml)||void 0};
ew.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
ea.Object.defineProperties(ew.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function fw(){}
v(fw,zu);fw.prototype.j=function(){return dw};
fw.prototype.h=function(a){return ts(a,Ll)||void 0};
fw.prototype.i=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
ea.Object.defineProperties(fw.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function gw(){}
v(gw,zu);gw.prototype.j=function(){return $v};
gw.prototype.h=function(a){return ts(a,Ok)||void 0};
gw.prototype.i=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
ea.Object.defineProperties(gw.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function hw(){}
v(hw,zu);hw.prototype.j=function(){return aw};
hw.prototype.h=function(a){return ts(a,Kl)||void 0};
hw.prototype.i=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function iw(){}
v(iw,zu);iw.prototype.j=function(){return bw};
iw.prototype.h=function(a){return ts(a,Jl)||void 0};
iw.prototype.i=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function jw(){}
v(jw,zu);jw.prototype.j=function(){return Zv};
jw.prototype.h=function(a){return ts(a,Il)};
jw.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var kw=new hs("NETWORK_SLI_TOKEN");function lw(a){this.h=a}
lw.prototype.fetch=function(a,b){var c=this,d,e,f;return w(function(g){c.h&&(d=vc(wc(5,Jc(a,"key")))||"/UNKNOWN_PATH",c.h.start(d));e=b;R("wug_networking_gzip_request")&&(e=Yp(b));f=new window.Request(a,e);return R("web_fetch_promise_cleanup_killswitch")?g.return(Promise.resolve(fetch(f).then(function(h){return c.handleResponse(h)}).catch(function(h){xt(h)}))):g.return(fetch(f).then(function(h){return c.handleResponse(h)}).catch(function(h){xt(h)}))})};
lw.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Df(),b=b.then(function(c){xt(new un("Error: API fetch failed",a.status,a.url,c));return Object.assign({},c,{errorMetadata:{status:a.status}})}));
return b};
lw[gs]=[new is(kw)];var mw=new hs("NETWORK_MANAGER_TOKEN");var nw;function ow(){var a=pw,b=qw,c=rw;this.l=sw;this.navigate=a;this.i=b;this.j=c;this.h=new Set}
function tw(a,b,c){if(uw(b))vw(a,b,c);else{var d=a.l(b,c);if(null==c?0:c.qc)d.qc=c.qc;0===d.type?a.navigate?ww(d.command)?xw(a,d.command)||(b=a.navigate(d)||[],Pf(b).then(function(){a.h.delete(d.command)})):wt(Error("Error: Command handler page requests need to specify a url.")):wt(Error("Error: Command handler navigate function was called but not set.")):1===d.type?a.i?xw(a,d.command)||(b=a.i(d),Pf(b).then(function(){a.h.delete(d.command)})):wt(Error("Error: Command handler handle service request function was called but not set.")):
2===d.type&&(a.j?a.j(d):wt(Error("Error: Command handler send action was called but not set.")))}}
function xw(a,b){if(a.h.has(b))return!0;a.h.add(b);return!1}
function uw(a){var b=!!ts(a,xk),c;a="CLIENT_SIGNAL"===(null==(c=ts(a,Mk))?void 0:c.signal);return b||a}
function vw(a,b,c){var d=ts(b,xk);if(d)var e=(null==d?void 0:d.commands)||[];else{var f;if("CLIENT_SIGNAL"===(null==(f=ts(b,Mk))?void 0:f.signal)){var g;e=(null==(g=ts(b,Mk))?void 0:g.actions)||[]}}if(e)for(b=t(e),e=b.next();!e.done;e=b.next()){e=e.value;try{tw(a,e,c)}catch(h){h instanceof Error&&wt(h)}}else wt(Error("Could not handle the meta command."))}
function ww(a){var b;return!(null==(b=ts(null==a?void 0:a.commandMetadata,Lk))||!b.url)}
;function yw(){var a,b,c;return w(function(d){if(1==d.h)return a=ns().resolve(Yv),a?d.yield(Tv(a),2):(xt(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return xt(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.Bf;return d.return(c)}xt(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;var zw=x.caches,Aw;function Bw(a){var b=a.indexOf(":");return-1===b?{ud:a}:{ud:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Cw(){return w(function(a){if(void 0!==Aw)return a.return(Aw);Aw=new Promise(function(b){var c;return w(function(d){switch(d.h){case 1:return Aa(d,2),d.yield(zw.open("test-only"),4);case 4:return d.yield(zw.delete("test-only"),5);case 5:Ba(d,3);break;case 2:if(c=Ca(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(Aw)})}
function Dw(a){var b,c,d,e,f,g,h;w(function(l){if(1==l.h)return l.yield(Cw(),2);if(3!=l.h){if(!l.i)return l.return(!1);b=[];return l.yield(zw.keys(),3)}c=l.i;d=t(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Bw(f),h=g.datasyncId,!h||a.includes(h)||b.push(zw.delete(f));return l.return(Promise.all(b).then(function(m){return m.some(function(p){return p})}))})}
function Ew(){var a,b,c,d,e,f,g;return w(function(h){if(1==h.h)return h.yield(Cw(),2);if(3!=h.h){if(!h.i)return h.return(!1);a=wn("cache contains other");return h.yield(zw.keys(),3)}b=h.i;c=t(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=Bw(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Fw(){try{return!!self.localStorage}catch(a){return!1}}
;function Gw(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function Hw(a){if(Fw()){var b=Object.keys(window.localStorage);b=t(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Gw(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function Iw(){if(!Fw())return!1;var a=wn(),b=Object.keys(window.localStorage);b=t(b);for(var c=b.next();!c.done;c=b.next())if(c=Gw(c.value),void 0!==c&&c!==a)return!0;return!1}
;function Jw(){yw().then(function(a){a&&(ap(a),Dw(a),Hw(a))})}
function Kw(){var a=new Pq;si.ma(function(){var b,c,d,e;return w(function(f){switch(f.h){case 1:if(R("ytidb_clear_optimizations_killswitch")){f.A(2);break}b=wn("clear");if(b.startsWith("V")&&b.endsWith("||")){var g=[b];ap(g);Dw(g);Hw(g);return f.return()}c=Iw();return f.yield(Ew(),3);case 3:return d=f.i,f.yield(bp(),4);case 4:if(e=f.i,!c&&!d&&!e)return f.return();case 2:a.sa()?Jw():a.l.add("publicytnetworkstatus-online",Jw,!0,void 0,void 0),f.h=0}})})}
;var Xh=ha(["data-"]);function Lw(a){a&&(a.dataset?a.dataset[Mw("loaded")]="true":Wh(a))}
function Nw(a,b){return a?a.dataset?a.dataset[Mw(b)]:a.getAttribute("data-"+b):null}
var Ow={};function Mw(a){return Ow[a]||(Ow[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Pw=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,Qw=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function Rw(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Pw,""),c=c.replace(Qw,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else Sw(a,b,c)}
function Sw(a,b,c){c=void 0===c?null:c;var d=Tw(a),e=document.getElementById(d),f=e&&Nw(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=$r(d,b),b=""+Ta(b),Uw[b]=f),g||(e=Vw(a,d,function(){if(!Nw(e,"loaded")){Lw(e);cs(d);var h=Za(ds,d);um(h,0)}},c)))}
function Vw(a,b,c,d){d=void 0===d?null:d;var e=tf("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);$h(e,tk(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function Ww(a){a=Tw(a);var b=document.getElementById(a);b&&(ds(a),b.parentNode.removeChild(b))}
function Xw(a,b){a&&b&&(a=""+Ta(b),(a=Uw[a])&&bs(a))}
function Tw(a){var b=document.createElement("a");nc(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+tc(a)}
var Uw={};var Yw=[],Zw=!1;function $w(){if(!R("disable_biscotti_fetch_for_ad_blocker_detection")&&!R("disable_biscotti_fetch_entirely_for_all_web_clients")&&Zt()){var a=O("PLAYER_VARS",{});if("1"!=qb(a)&&!$t(a)){var b=function(){Zw=!0;"google_ad_status"in window?Vl("DCLKSTAT",1):Vl("DCLKSTAT",2)};
try{Rw("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Yw.push(si.ma(function(){if(!(Zw||"google_ad_status"in window)){try{Xw("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Zw=!0;Vl("DCLKSTAT",3)}},5E3))}}}
function ax(){var a=Number(O("DCLKSTAT",0));return isNaN(a)?0:a}
;var bx=window;function cx(){var a,b;return"h5vcc"in bx&&(null==(a=bx.h5vcc.traceEvent)?0:a.traceBegin)&&(null==(b=bx.h5vcc.traceEvent)?0:b.traceEnd)?1:"performance"in bx&&bx.performance.mark&&bx.performance.measure?2:0}
function dx(a){switch(cx()){case 1:bx.h5vcc.traceEvent.traceBegin("YTLR",a);break;case 2:bx.performance.mark(a+"-start");break;case 0:break;default:Yh()}}
function ex(a){switch(cx()){case 1:bx.h5vcc.traceEvent.traceEnd("YTLR",a);break;case 2:var b=a+"-start",c=a+"-end";bx.performance.mark(c);bx.performance.measure(a,b,c);break;case 0:break;default:Yh()}}
;var fx=R("web_enable_lifecycle_monitoring")&&0!==cx();function gx(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?Cn():d;this.j=c;this.scheduler=d;this.i=new Nh;this.h=a;for(a={Za:0};a.Za<this.h.length;a={Db:a.Db,Za:a.Za},a.Za++)a.Db=this.h[a.Za],c=function(e){return function(){e.Db.Ec();b.h[e.Za].kc=!0;b.h.every(function(f){return!0===f.kc})&&b.i.resolve()}}(a),d=this.getPriority(a.Db),d=zn(c,d),this.h[a.Za]=Object.assign({},a.Db,{Ec:c,
jobId:d})}
function hx(a){var b=Array.from(a.h.keys()).sort(function(d,e){return a.getPriority(a.h[e])-a.getPriority(a.h[d])});
b=t(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],void 0===c.jobId||c.kc||(a.scheduler.Fa(c.jobId),zn(c.Ec,10))}
gx.prototype.cancel=function(){for(var a=t(this.h),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.jobId||b.kc||this.scheduler.Fa(b.jobId),b.kc=!0;this.i.resolve()};
gx.prototype.getPriority=function(a){var b;return null!=(b=a.priority)?b:this.j};function ix(a){this.state=a;this.plugins=[];this.s=void 0;this.v={};fx&&dx(this.state)}
k=ix.prototype;k.install=function(a){this.plugins.push(a);return this};
k.uninstall=function(){var a=this;Ma.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);-1<b&&a.plugins.splice(b,1)})};
k.transition=function(a,b){var c=this;fx&&ex(this.state);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.to===a}):f.from===c.state&&f.to===a});
if(d){this.j&&(hx(this.j),this.j=void 0);jx(this,a,b);this.state=a;fx&&dx(this.state);d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(kx(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function kx(a,b){var c=b.filter(function(e){return 10===lx(a,e)}),d=b.filter(function(e){return 10!==lx(a,e)});
return a.v.Pf?function(){var e=Ma.apply(0,arguments);return w(function(f){if(1==f.h)return f.yield(a.He.apply(a,[c].concat(ia(e))),2);a.Dd.apply(a,[d].concat(ia(e)));f.h=0})}:function(){var e=Ma.apply(0,arguments);
a.Ie.apply(a,[c].concat(ia(e)));a.Dd.apply(a,[d].concat(ia(e)))}}
k.Ie=function(a){var b=Ma.apply(1,arguments);Cn();for(var c={},d=t(a),e=d.next();!e.done;c={mb:c.mb},e=d.next())c.mb=e.value,An(function(f){return function(){xx(f.mb.name);f.mb.callback.apply(f.mb,ia(b));yx(f.mb.name)}}(c))};
k.He=function(a){var b=Ma.apply(1,arguments),c,d,e,f;return w(function(g){1==g.h&&(Cn(),c={},d=t(a),e=d.next());if(3!=g.h){if(e.done)return g.A(0);c.ab=e.value;c.Bb=void 0;f=function(h){return function(){xx(h.ab.name);var l=h.ab.callback.apply(h.ab,ia(b));"function"===typeof(null==l?void 0:l.then)?h.Bb=l.then(function(){yx(h.ab.name)}):yx(h.ab.name)}}(c);
An(f);return c.Bb?g.yield(c.Bb,3):g.A(3)}c={ab:c.ab,Bb:c.Bb};e=d.next();return g.A(2)})};
k.Dd=function(a){var b=Ma.apply(1,arguments),c=this,d=a.map(function(e){return{Ec:function(){xx(e.name);e.callback.apply(e,ia(b));yx(e.name)},
priority:lx(c,e)}});
d.length&&(this.j=new gx(d))};
function lx(a,b){var c,d;return null!=(d=null!=(c=a.s)?c:b.priority)?d:0}
function xx(a){fx&&a&&dx(a)}
function yx(a){fx&&a&&ex(a)}
function jx(a,b,c){fx&&console.groupCollapsed&&console.groupEnd&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
ea.Object.defineProperties(ix.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function zx(a){ix.call(this,void 0===a?"document_active":a);var b=this;this.s=10;this.h=new Map;this.transitions=[{from:"document_active",to:"document_disposed_preventable",action:this.ga},{from:"document_active",to:"document_disposed",action:this.l},{from:"document_disposed_preventable",to:"document_disposed",action:this.l},{from:"document_disposed_preventable",to:"flush_logs",action:this.m},{from:"document_disposed_preventable",to:"document_active",action:this.i},{from:"document_disposed",to:"flush_logs",
action:this.m},{from:"document_disposed",to:"document_active",action:this.i},{from:"document_disposed",to:"document_disposed",action:function(){}},
{from:"flush_logs",to:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
v(zx,ix);zx.prototype.ga=function(a,b){if(!this.h.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
zx.prototype.l=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
zx.prototype.m=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
zx.prototype.i=function(){this.h=new Map};function Ax(a){ix.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",to:"document_visible",action:this.i},{from:"document_visibility_unknown",to:"document_hidden",action:this.h},{from:"document_visibility_unknown",to:"document_foregrounded",action:this.m},{from:"document_visibility_unknown",to:"document_backgrounded",action:this.l},{from:"document_visible",to:"document_hidden",action:this.h},{from:"document_visible",to:"document_foregrounded",
action:this.m},{from:"document_visible",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_visible",action:this.i},{from:"document_foregrounded",to:"document_hidden",action:this.h},{from:"document_foregrounded",to:"document_foregrounded",action:this.m},{from:"document_hidden",to:"document_visible",action:this.i},{from:"document_hidden",to:"document_backgrounded",action:this.l},{from:"document_hidden",to:"document_hidden",action:this.h},{from:"document_backgrounded",to:"document_hidden",
action:this.h},{from:"document_backgrounded",to:"document_backgrounded",action:this.l},{from:"document_backgrounded",to:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
R("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
v(Ax,ix);Ax.prototype.i=function(a,b){a(null==b?void 0:b.event);R("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Ax.prototype.h=function(a,b){a(null==b?void 0:b.event);R("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Ax.prototype.l=function(a,b){a(null==b?void 0:b.event)};
Ax.prototype.m=function(a,b){a(null==b?void 0:b.event)};function Bx(){this.j=new zx;this.l=new Ax}
Bx.prototype.install=function(){var a=Ma.apply(0,arguments),b=this;a.forEach(function(c){b.j.install(c)});
a.forEach(function(c){b.l.install(c)})};function Cx(){Bx.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));a={};this.install((a.flush_logs={callback:this.i},a))}
v(Cx,Bx);Cx.prototype.i=function(){if(R("web_fp_via_jspb")){var a=new $k,b=Nt();b&&F(a,1,b);b=R("jspb_sparse_encoded_pivot")?new Cl([{}]):new Cl;ce(b,$k,380,Dl,a);pt(b);R("web_fp_via_jspb_and_json")&&Mn("finalPayload",{csn:Nt()})}else Mn("finalPayload",{csn:Nt()})};
Cx.prototype.h=function(){Ct(Dt)};function Dx(){}
function Ex(){var a=B("ytglobal.storage_");a||(a=new Dx,A("ytglobal.storage_",a));return a}
Dx.prototype.estimate=function(){var a,b,c;return w(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(Fx()):d.return()})};
function Fx(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
A("ytglobal.storageClass_",Dx);function Kn(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=om("ytidb_transaction_ended_event_rate_limit_session",.2)}
Kn.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":R("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":R("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":Gx(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=om("ytidb_transaction_ended_event_rate_limit_transaction",.1)&&this.h("idbTransactionEnded",
b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function Gx(a,b){Ex().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:Hx(null==c?void 0:c.usage),deviceStorageQuotaMbytes:Hx(null==c?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function Hx(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function Ix(a){this.args=void 0===a?null:a;this.returnValue=[]}
;var Jx=new Map;function Kx(a,b){if(!a)return null;a=Object.keys(a);a=t(a);for(var c=a.next();!c.done;c=a.next()){c=c.value;var d=c.toLowerCase();if(-1<d.indexOf(b,d.length-b.length))return c}return null}
;function Lx(a,b,c){var d;d||(d={bubbles:!0,cancelable:!1,composed:!0});null!==c&&void 0!==c&&(d.detail=c);b=new CustomEvent(b,d);a.dispatchEvent(b)}
;function Mx(a,b){b=new Ix(b);Lx(a,"yt-action",b);return b.returnValue}
function Nx(a,b,c,d){b&&b.length&&b.forEach(function(e){var f=Kx(e,"action")||Kx(e,"command")||Kx(e,"endpoint");if(f){var g="yt"+f;var h=Jx.get(g);h?g=h:(f="yt-"+f.replace(/([A-Z])/g,"-$1").toLowerCase(),Jx.set(g,f),g=f);ts(e,Kk)&&(g+="-"+ts(e,Kk).signal.toLowerCase().replace(/_/g,"-"))}else g=null;g&&(R("handle_service_request_actions")&&e.commandMetadata&&e.commandMetadata.webCommandMetadata&&e.commandMetadata.webCommandMetadata.sendPost?c&&R("use_source_element_if_present_for_actions")?Ox(c,[e]):
Ox(a,[e]):Mx(a,[e,c,d]))})}
function Ox(a,b){var c=[a];b&&c.push.apply(c,b);b=Mx(a,c);return 0<b.length&&(b=b[0],Lx(a,"yt-service-request-sent",b),b&&b.ajaxPromise)?(b.ajaxPromise.then(function(d){Lx(a,"yt-service-request-completed",d)},function(d){Lx(a,"yt-service-request-error",{error:d,
params:c})},a),b.ajaxPromise):Lf()}
;function sw(a,b,c){b=void 0===b?{}:b;var d,e=null==(d=ts(a.commandMetadata,Lk))?void 0:d.url;d=b.form||{};!c||d.element||d.skipDefaultElement||(b.form=b.form||{},b.form.element=c);if(e&&"/service_ajax"!==e)return{type:0,command:a,form:b.form};if(R("kevlar_service_command_check")){if(c=ns().resolve(Yv),tu(a,c.j))return Object.assign({},{type:1,command:a},b)}else{var f;if(null==(f=ts(a.commandMetadata,Lk))?0:f.apiUrl)return Object.assign({},{type:1,command:a},b)}return{type:2,command:a,form:b.form}}
function qw(a){if(a.form){var b=a.form,c=Object.assign({},b);b=b.element;c=(delete c.element,c);if(b)return[Ox(b,[a.command,c,a.qc])]}return[]}
function rw(a){if(a.form){var b=a.form,c=Object.assign({},b);b=b.element;c=(delete c.element,c);b&&Nx(b,[a.command],b,c)}}
;function Px(a,b,c){J.call(this);var d=this;c=c||O("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.j=b||null;this.targetOrigin="*";this.l=c;this.sessionId=null;this.channel="widget";this.M=!!a;this.v=function(e){a:if(!("*"!=d.l&&e.origin!=d.l||d.j&&e.source!=d.j||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.M&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.l=d.targetOrigin=e.origin);d.j=e.source;d.sessionId=f.id;d.i&&(d.i(),d.i=null);break;case "command":d.m&&(!d.s||0<=fb(d.s,f.func))&&d.m(f.func,f.args,e.origin)}}};
this.s=this.i=this.m=null;window.addEventListener("message",this.v)}
v(Px,J);Px.prototype.sendMessage=function(a,b){if(b=b||this.j){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){am(d)}}};
Px.prototype.K=function(){window.removeEventListener("message",this.v);J.prototype.K.call(this)};function Qx(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new Px(!!O("WIDGET_ID_ENFORCE")),b=this.Ce.bind(this);a.m=b;a.s=null;this.h.channel="widget";if(a=O("WIDGET_ID"))this.h.sessionId=a}
k=Qx.prototype;k.Ce=function(a,b,c){"addEventListener"===a&&b?this.Dc(b[0],c):this.Tc(a,b,c)};
k.Tc=function(){};
k.wc=function(a){var b=this;return function(c){return b.sendMessage(a,c)}};
k.Dc=function(a,b){this.j[a]||"onReady"===a||(this.addEventListener(a,this.wc(a,b)),this.j[a]=!0)};
k.addEventListener=function(){};
k.he=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.zc());this.sendMessage("onReady");gb(this.i,this.Bd,this);this.i=[]};
k.zc=function(){return null};
function Rx(a,b){a.sendMessage("infoDelivery",b)}
k.Bd=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
k.sendMessage=function(a,b){this.Bd({event:a,info:void 0===b?null:b})};
k.dispose=function(){this.h=null};var Sx={},Tx=(Sx["api.invalidparam"]=2,Sx.auth=150,Sx["drm.auth"]=150,Sx["heartbeat.net"]=150,Sx["heartbeat.servererror"]=150,Sx["heartbeat.stop"]=150,Sx["html5.unsupportedads"]=5,Sx["fmt.noneavailable"]=5,Sx["fmt.decode"]=5,Sx["fmt.unplayable"]=5,Sx["html5.missingapi"]=5,Sx["html5.unsupportedlive"]=5,Sx["drm.unavailable"]=5,Sx["mrm.blocked"]=151,Sx);var Ux=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function Vx(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function Wx(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=t(Ux);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function Xx(a,b,c,d){if(Sa(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Yx(a){Qx.call(this);this.listeners=[];this.l=!1;this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.Oe.bind(this));this.addEventListener("onVolumeChange",this.Pe.bind(this));this.addEventListener("onApiChange",this.Je.bind(this));this.addEventListener("onPlaybackQualityChange",this.Le.bind(this));this.addEventListener("onPlaybackRateChange",this.Me.bind(this));this.addEventListener("onStateChange",this.Ne.bind(this));this.addEventListener("onWebglSettingsChanged",
this.Qe.bind(this))}
v(Yx,Qx);k=Yx.prototype;
k.Tc=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&Vx(a)){var d=b;if(Sa(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=Wx(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=Wx(e);break;case "loadPlaylist":case "cuePlaylist":e=Xx(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);Vx(a)&&Rx(this,this.zc())}};
k.Dc=function(a,b){"onReady"===a?this.api.logApiCall(a+" invocation",b):"onError"===a&&this.l&&(this.api.logApiCall(a+" invocation",b,this.errorCode),this.errorCode=void 0);this.api.logApiCall(a+" registration",b);Qx.prototype.Dc.call(this,a,b)};
k.wc=function(a,b){var c=this,d=Qx.prototype.wc.call(this,a,b);return function(e){"onError"===a?c.api.logApiCall(a+" invocation",b,e):c.api.logApiCall(a+" invocation",b);d(e)}};
k.onReady=function(){var a=this.he.bind(this);this.h.i=a;a=this.api.getVideoData();if(!a.isPlayable){this.l=!0;a=a.errorCode;var b=void 0===b?5:b;this.errorCode=a?Tx[a]||b:b;this.sendMessage("onError",this.errorCode.toString())}};
k.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
k.zc=function(){if(!this.api)return null;var a=this.api.getApiInterface();kb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
k.Ne=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());Rx(this,a)};
k.Le=function(a){Rx(this,{playbackQuality:a})};
k.Me=function(a){Rx(this,{playbackRate:a})};
k.Je=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);a.join(", ");b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var l=f[g],m=this.api.getOption(e,l);b[e][l]=m}}this.sendMessage("apiInfoDelivery",b)};
k.Pe=function(){Rx(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
k.Oe=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Rx(this,a)};
k.Qe=function(){var a={sphericalProperties:this.api.getSphericalProperties()};Rx(this,a)};
k.dispose=function(){Qx.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function Zx(a){J.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.xd,this)}
v(Zx,J);k=Zx.prototype;k.start=function(){this.started||this.h()||(this.started=!0,this.connection.ib("RECEIVING"))};
k.ib=function(a,b){this.started&&!this.h()&&this.connection.ib(a,b)};
k.xd=function(a,b,c){if(this.started&&!this.h()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=$x(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=ay(a,c))&&this.ib(a,c))}}};
k.addListener=function(a){if(!(a in this.i)){var b=this.Ke.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
k.Ke=function(a,b){this.started&&!this.h()&&this.connection.ib(a,this.yc(a,b))};
k.yc=function(a,b){if(null!=b)return{value:b}};
k.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
k.K=function(){var a=this.connection;a.h()||Qi(a.i,"command",this.xd,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);J.prototype.K.call(this)};function by(a,b){Zx.call(this,b);this.api=a;this.start()}
v(by,Zx);by.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
by.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function $x(a,b){switch(a){case "loadVideoById":return a=Wx(b),[a];case "cueVideoById":return a=Wx(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=Xx(b),[a];case "cuePlaylist":return a=Xx(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function ay(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
by.prototype.yc=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Zx.prototype.yc.call(this,a,b)};
by.prototype.K=function(){Zx.prototype.K.call(this);delete this.api};function cy(a){a=void 0===a?!1:a;J.call(this);this.i=new Pi(a);Ae(this,this.i)}
$a(cy,J);cy.prototype.subscribe=function(a,b,c){return this.h()?0:this.i.subscribe(a,b,c)};
cy.prototype.m=function(a,b){this.h()||this.i.bb.apply(this.i,arguments)};function dy(a,b,c){cy.call(this);this.l=a;this.j=b;this.id=c}
v(dy,cy);dy.prototype.ib=function(a,b){this.h()||this.l.ib(this.j,this.id,a,b)};
dy.prototype.K=function(){this.j=this.l=null;cy.prototype.K.call(this)};function ey(a,b,c){J.call(this);this.i=a;this.origin=c;this.j=Nr(window,"message",this.l.bind(this));this.connection=new dy(this,a,b);Ae(this,this.connection)}
v(ey,J);ey.prototype.ib=function(a,b,c,d){this.h()||a!==this.i||(a={id:b,command:c},d&&(a.data=d),this.i.postMessage(JSON.stringify(a),this.origin))};
ey.prototype.l=function(a){if(!this.h()&&a.origin===this.origin){var b=a.data;if("string"===typeof b){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.h()||c.m("command",b.command,b.data,a.origin)}}}};
ey.prototype.K=function(){Or(this.j);this.i=null;J.prototype.K.call(this)};function fy(){this.state=1;this.h=null}
k=fy.prototype;k.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterUrl)?d:null;if(a.interpreterSafeScript){d=a.interpreterSafeScript.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var f=xb();d=f?f.createScript(d):d;d=new Cb(d,Bb)}else d=null!=(f=a.interpreterScript)?f:null;a.interpreterSafeUrl&&(e=a.interpreterSafeUrl,Ab("From proto message. b/166824318"),e=Gb(e.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());gy(this,d,e,a.program,b,c)}else xt(Error("Cannot initialize botguard without program"))};
function gy(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,Rw(c,function(){window[g]?hy(a,d,g,e):(a.state=3,Ww(c),xt(new un("Unable to load Botguard","from "+c)))},f)):b?(f=tf("SCRIPT"),b instanceof Cb?(b instanceof Cb&&b.constructor===Cb?b=b.j:(Qa(b),b="type_error:SafeScript"),f.textContent=b,Zh(f)):f.textContent=b,f.nonce=rc(),document.head.appendChild(f),document.head.removeChild(f),window[g]?hy(a,d,g,e):(a.state=4,xt(new un("Unable to load Botguard from JS")))):xt(new un("Unable to load VM; no url or JS provided"))}
function hy(a,b,c,d){a.state=5;try{var e=new Oh({program:b,me:c,De:R("att_web_record_metrics")});e.Se.then(function(){a.state=6;d&&d(b)});
a.Oc(e)}catch(f){a.state=7,f instanceof Error&&xt(f)}}
k.invoke=function(a){a=void 0===a?{}:a;return this.Rc()?this.Kd({cd:a}):null};
k.dispose=function(){this.Uc()};
k.Uc=function(){this.Oc(null);this.state=8};
k.Rc=function(){return!!this.h};
k.Kd=function(a){return this.h.Ed(a)};
k.Oc=function(a){ye(this.h);this.h=a};function iy(){var a=B("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function jy(){fy.apply(this,arguments)}
v(jy,fy);jy.prototype.Uc=function(){this.state=8};
jy.prototype.Oc=function(a){var b;null==(b=iy())||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.Ed.bind(a)},A("yt.abuse.playerAttLoader",b),A("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(A("yt.abuse.playerAttLoader",null),A("yt.abuse.playerAttLoaderRun",null))};
jy.prototype.Rc=function(){return!!iy()};
jy.prototype.Kd=function(a){return iy().bgvmc(a)};var ky=new jy;function ly(){return ky.Rc()}
function my(a){a=void 0===a?{}:a;return ky.invoke(a)}
;function ny(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||sb(b);this.assets=a.assets||{};this.attrs=a.attrs||sb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
ny.prototype.clone=function(){var a=new ny,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Qa(c)?a[b]=sb(c):a[b]=c}return a};var oy=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function py(a){a=a||"";if(window.spf){var b=a.match(oy);spf.style.load(a,b?b[1]:"",void 0)}else qy(a)}
function qy(a){var b=ry(a),c=document.getElementById(b),d=c&&Nw(c,"loaded");d||c&&!d||(c=sy(a,b,function(){if(!Nw(c,"loaded")){Lw(c);cs(b);var e=Za(ds,b);um(e,0)}}))}
function sy(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=tk(a);oc(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function ry(a){var b=tf("A");nc(b,new Kb(a,Pb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+tc(a)}
;function ty(){J.call(this);this.i=[]}
v(ty,J);ty.prototype.K=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.callback,void 0)}J.prototype.K.call(this)};function uy(){ty.apply(this,arguments)}
v(uy,ty);function vy(a,b,c,d,e){J.call(this);var f=this;this.v=b;this.webPlayerContextConfig=d;this.Sb=e;this.ya=!1;this.api={};this.ka=this.s=null;this.W=new Pi;this.i={};this.aa=this.Da=this.elementId=this.pb=this.config=null;this.Z=!1;this.l=this.M=null;this.la={};this.Tb=["onReady"];this.lastError=null;this.Fb=NaN;this.T={};this.Ub=new uy(this);this.da=0;this.j=this.m=a;Ae(this,this.W);wy(this);xy(this);Ae(this,this.Ub);c?this.da=um(function(){f.loadNewVideoConfig(c)},0):d&&(yy(this),zy(this))}
v(vy,J);k=vy.prototype;k.getId=function(){return this.v};
k.loadNewVideoConfig=function(a){if(!this.h()){this.da&&(window.clearTimeout(this.da),this.da=0);var b=a||{};b instanceof ny||(b=new ny(b));this.config=b;this.setConfig(a);zy(this);this.isReady()&&Ay(this)}};
function yy(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.v,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.v:a.config.attrs.id=a.v);var c;(null==(c=a.j)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
k.setConfig=function(a){this.pb=a;this.config=By(a);yy(this);if(!this.Da){var b;this.Da=Cy(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.j&&(this.j.style.width=ji(Number(b)||b)),(a=a.height)&&this.j&&(this.j.style.height=ji(Number(a)||a))};
function Ay(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function Dy(a){var b=!0,c=Ey(a);c&&a.config&&(a=Fy(a),b=Nw(c,"version")===a);return b&&!!B("yt.player.Application.create")}
function zy(a){if(!a.h()&&!a.Z){var b=Dy(a);if(b&&"html5"===(Ey(a)?"html5":null))a.aa="html5",a.isReady()||Gy(a);else if(Hy(a),a.aa="html5",b&&a.l&&a.m)a.m.appendChild(a.l),Gy(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.M=function(){c=!0;var d=Iy(a,"player_bootstrap_method")?B("yt.player.Application.createAlternate")||B("yt.player.Application.create"):B("yt.player.Application.create");var e=a.config?By(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig,a.Sb);Gy(a)};
a.Z=!0;b?a.M():(Rw(Fy(a),a.M),(b=Jy(a))&&py(b),Ky(a)&&!c&&A("yt.player.Application.create",null))}}}
function Ey(a){var b=sf(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function Gy(a){if(!a.h()){var b=Ey(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.Z=!1;if(!Iy(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}Ly(a)}else a.Fb=um(function(){Gy(a)},50)}}
function Ly(a){wy(a);a.ya=!0;var b=Ey(a);if(b){a.s=My(a,b,"addEventListener");a.ka=My(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=My(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.s&&a.s(g,a.i[g]);Ay(a);a.Da&&a.Da(a.api);a.W.bb("onReady",a.api)}
function My(a,b,c){var d=b[c];return function(){var e=Ma.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,xt(f))}}}
function wy(a){a.ya=!1;if(a.ka)for(var b in a.i)a.i.hasOwnProperty(b)&&a.ka(b,a.i[b]);for(var c in a.T)a.T.hasOwnProperty(c)&&window.clearTimeout(Number(c));a.T={};a.s=null;a.ka=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.pb};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
k.isReady=function(){return this.ya};
function xy(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){cs("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){cs("WATCH_LATER_VIDEO_REMOVED",b)})}
k.addEventListener=function(a,b){var c=this,d=Cy(this,b);d&&(0<=fb(this.Tb,a)||this.i[a]||(b=Ny(this,a),this.s&&this.s(a,b)),this.W.subscribe(a,d),"onReady"===a&&this.isReady()&&um(function(){d(c.api)},0))};
k.removeEventListener=function(a,b){this.h()||(b=Cy(this,b))&&Qi(this.W,a,b)};
function Cy(a,b){var c=b;if("string"===typeof b){if(a.la[b])return a.la[b];c=function(){var d=Ma.apply(0,arguments),e=B(b);if(e)try{e.apply(x,d)}catch(f){wt(f)}};
a.la[b]=c}return c?c:null}
function Ny(a,b){var c="ytPlayer"+b+a.v;a.i[b]=c;x[c]=function(d){var e=um(function(){if(!a.h()){try{a.W.bb(b,null!=d?d:void 0)}catch(h){xt(new un("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.v,data:d}))}var f=a.T,g=String(e);g in f&&delete f[g]}},0);
pb(a.T,String(e))};
return c}
k.getPlayerType=function(){return this.aa||(Ey(this)?"html5":null)};
k.getLastError=function(){return this.lastError};
function Hy(a){a.cancel();wy(a);a.aa=null;a.config&&(a.config.loaded=!1);var b=Ey(a);b&&(Dy(a)||!Ky(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
k.cancel=function(){this.M&&Xw(Fy(this),this.M);window.clearTimeout(this.Fb);this.Z=!1};
k.K=function(){Hy(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){wt(b)}this.la=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(x[this.i[a]]=null);this.pb=this.config=this.api=null;delete this.m;delete this.j;J.prototype.K.call(this)};
function Ky(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function Fy(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function Jy(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function Iy(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return"true"===dm(c||"","&")[b]}
function By(a){for(var b={},c=t(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?sb(e):e}return b}
;var Oy={},Py="player_uid_"+(1E9*Math.random()>>>0);function Qy(a,b){var c="player",d=!1;d=void 0===d?!0:d;c="string"===typeof c?sf(c):c;var e=Py+"_"+Ta(c),f=Oy[e];if(f&&d)return Ry(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new vy(c,e,a,b,void 0);Oy[e]=f;cs("player-added",f.api);Be(f,function(){delete Oy[f.getId()]});
return f.api}
function Ry(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var Sy=null,Ty=null,Uy=null;function Vy(){Wy()}
function Xy(){Wy()}
function Wy(){var a=Sy.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function pw(a){var b,c;if(a=null==(b=a.command)?void 0:null==(c=b.urlEndpoint)?void 0:c.url)b=window,c=Sh(a),void 0!==c&&b.open(c,void 0,void 0);return[]}
function Yy(){Sy&&Sy.sendAbandonmentPing&&Sy.sendAbandonmentPing();O("PL_ATT")&&ky.dispose();for(var a=si,b=0,c=Yw.length;b<c;b++)a.Fa(Yw[b]);Yw.length=0;Ww("//static.doubleclick.net/instream/ad_status.js");Zw=!1;Vl("DCLKSTAT",0);ze(Uy,Ty);Sy&&(Sy.removeEventListener("onVideoDataChange",Vy),Sy.destroy())}
;function Zy(a,b,c){a="ST-"+tc(a).toString(36);b=b?Cc(b):"";c=c||5;Zt()&&bn(a,b,c)}
;function $y(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=O("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=O("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=xc(window.location.href);g&&f.push(g);g=xc(d);if(0<=fb(f,g)||!g&&0==d.lastIndexOf("/",0))if(R("autoescape_tempdata_url")&&(f=document.createElement("a"),nc(f,d),d=f.href),d&&(d=yc(d),f=d.indexOf("#"),d=0>f?d:d.slice(0,f)))if(e&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:Nt()},b)),h){var h=parseInt(h,10);isFinite(h)&&0<h&&
Zy(d,b,h)}else Zy(d,b)}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var l=void 0===l?{}:l;var m=void 0===m?"":m;var p=void 0===p?window:p;c=p.location;a=Ec(a,l)+m;var r=void 0===r?ci:r;a:{r=void 0===r?ci:r;for(l=0;l<r.length;++l)if(m=r[l],m instanceof ai&&m.se(a)){r=new Kb(a,Pb);break a}r=void 0}r=Sh(r||Qb);void 0!==r&&(c.href=r)}return!0}
;A("yt.setConfig",Vl);A("yt.config.set",Vl);A("yt.setMsg",Qt);A("yt.msgs.set",Qt);A("yt.logging.errors.log",wt);
A("writeEmbed",function(){var a=O("PLAYER_CONFIG");if(!a){var b=O("PLAYER_VARS");b&&(a={args:b})}iu(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=O("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);Jv("embed",["ol"]);c=O("WEB_PLAYER_CONTEXT_CONFIGS").WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=im(window.location.href);
d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}var e;(null==(e=a.args)?0:e.autoplay)&&Jv("watch",["pbs","pbu","pbp"]);Sy=Qy(a,c);R("embeds_enable_server_driven_watch_again_on_youtube")&&!ow.h&&(ow.h=new ow);Sy.addEventListener("onVideoDataChange",Vy);Sy.addEventListener("onReady",Xy);R("embeds_enable_server_driven_watch_again_on_youtube")&&Sy.addEventListener("innertubeCommand",function(f){tw(ow.h,f)});
a=O("POST_MESSAGE_ID","player");O("ENABLE_JS_API")?Uy=new Yx(Sy):O("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(Ty=new ey(window.parent,a,b),Uy=new by(Sy,Ty.connection));$w();R("ytidb_create_logger_embed_killswitch")||Jn();a={};Cx.h||(Cx.h=new Cx);Cx.h.install((a.flush_logs={callback:function(){Rs()}},a));
Dr();R("ytidb_clear_embedded_player")&&si.ma(function(){var f,g;if(!nw){var h=ns(),l={Lc:mw,Id:lw};h.h.set(l.Lc,l);l={sc:{feedbackEndpoint:vu(gw),modifyChannelNotificationPreferenceEndpoint:vu(hw),playlistEditEndpoint:vu(iw),subscribeEndpoint:vu(ew),unsubscribeEndpoint:vu(fw),webPlayerShareEntityServiceEndpoint:vu(jw)}};var m=su(),p={};m&&(p.client_location=m);void 0===f&&(f=Xm());void 0===g&&(g=h.resolve(mw));Sv(l,g,f,p);f={Lc:Yv,Jd:Rv.h};h.h.set(f.Lc,f);nw=h.resolve(Yv)}Kw()})});
var az=Zl(function(){Nv();ju()}),bz=Zl(function(a){a.persisted||(Nv(),ju())}),cz=Zl(function(a){R("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?Yy():a.persisted||Yy()}),dz=Zl(Yy);
window.addEventListener?(window.addEventListener("load",az),window.addEventListener("pageshow",bz),window.addEventListener("pagehide",cz)):window.attachEvent&&(window.attachEvent("onload",az),window.attachEvent("onunload",dz));A("yt.abuse.player.botguardInitialized",B("yt.abuse.player.botguardInitialized")||ly);A("yt.abuse.player.invokeBotguard",B("yt.abuse.player.invokeBotguard")||my);A("yt.abuse.dclkstatus.checkDclkStatus",B("yt.abuse.dclkstatus.checkDclkStatus")||ax);
A("yt.player.exports.navigate",B("yt.player.exports.navigate")||$y);A("yt.util.activity.init",B("yt.util.activity.init")||Sr);A("yt.util.activity.getTimeSinceActive",B("yt.util.activity.getTimeSinceActive")||Vr);A("yt.util.activity.setTimestamp",B("yt.util.activity.setTimestamp")||Tr);}).call(this);
