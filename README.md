# Front End Performance 

### Measuring Front End Performance

So far, we have spoken about problems on the server side that can make a webpage feel slow.  However, there are also problems on the client side that can have significant impacts on performance.

Take a look at the following railscast to understand some of the problems that occur, how to measure them, and then fix them.

* [Using Chrome Tools](https://www.youtube.com/watch?v=JXDoWPqydvg)

### React - not bad at all

Your project is probably using React.  And remember that react is, by design, a fairly performant library.  It first determines whether or not to update the Document Object Model (and how to most efficiently update the DOM), before proceeding with the update.  However, even performing that calculation can become costly.  

The following article takes this under consideration.

* [React rendering](https://robots.thoughtbot.com/react-rendering-misconception)

After reading about the costs of react rendering, read the following article.  It talks about the problems that occur with deeply nested components, and how to solve this problem.  It also talks about how to avoid useless re-renders when using redux.  Take a look.   

* [Optimizing React Performance](https://marmelab.com/blog/2017/02/06/react-is-slow-react-is-fast.html)

### Web Sockets

Finally, let's talk about web sockets.  Just as using Ajax allows us to update a webpage with data from the server without a page refresh, websockets allows the same thing.  However, using web sockets offers performance benefits, and as it allows servers to push events to the client - instead of the client checking to see if anything has changed on the server.  

Take a look at some of the performance benefits of websockets here:    

* [Web sockets benchmarks](http://blog.arungupta.me/rest-vs-websocket-comparison-benchmarks/)
* [Web sockets in context](https://websocket.org/quantum.html)


Then read a little bit more about how web sockets work: 

* [Web Sockets on the Web](http://blog.teamtreehouse.com/an-introduction-to-websockets)

Finally, learn about how to work with web sockets in the context of a rails application, with ActionCable.

* [ActionCable](https://blog.heroku.com/real_time_rails_implementing_websockets_in_rails_5_with_action_cable)

<p class='util--hide'>View <a href='https://learn.co/lessons/front-end-performance'>Front End Performance</a> on Learn.co and start learning to code for free.</p>
