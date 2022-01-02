# RxJS
RxJS study course
----------------------------------------------------------------------------
Q1. What is a stream?  
Ans: A continious flow of data over certain interval is called stream.
----------------------------------------------------------------------------
Q2. What is RXJS?
Ans: Reactive extensions for javascript.
----------------------------------------------------------------------------
Q3. What is the syntax of the subscribe method in observable?
Ans: 
      const formEvent$ = formEvent(document, 'click')
            formEvent$.subscribe(
              event=>{console.log(event},
              error=>{console.log(error)},
              ()=>{cons0le.log(`complete`)}
            )
----------------------------------------------------------------------------
