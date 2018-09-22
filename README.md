
Tech Stack Used in React:
- react lifecycle, particularly componentDidMount()



my question 1:

- onGuess() only setState 1 property. I am not sure if it will call render() and then call componentDidMount() to show next question. Seems like it does not. 

- nextQuestion() setState 3 properties out of 4. I think it will call render() and thereforce call componentDidMount()