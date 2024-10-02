# Conclusion

This course was very interesting and I learned a lot, but I would only give it a 6 out of 10 rating. The main reason is that LangChain seems to be moving very fast, and many elements of the course are already outdated. The deprecation warnings when running the example code are testament to the fast-moving pace, and some sections of the notebooks didn't even run anymore without adjustments. I would definitely welcome an updated version of this course, which could easily score a 10 out of 10. The low rating does not reflect bad content, but rather my hesitation to recommend this course to students wanting to learn about LangChain. Nonetheless, transferring the course content to my own examples was fun and educative. And maybe the challenge of having to rewrite some sections did not make this course easier, but it even enhanced the learning experience.

## Course Summary

Let's do a quick summary of the course.

- [**Chapter 2**](chapter2.ipynb) introduced prompt templates and output parsers for a structured way to create prompts and to extract information from the response of the LLM. For the toy use cases in my notebooks, this produced quite a bit of boilerplate code, but thinking ahead to more complex applications, there is a lot of value in these concepts.

- [**Chapter 3**](chapter3.ipynb) was all about memory, transitioning large language models from their stateless nature to stateful chat experiences. While this chapter was conceptually interesting, some of the use cases aimed at saving tokens felt outdated to me because the cost of tokens has rapidly declined over the past months (and this trend likely continues), but I cannot deny the value for long conversations. The clear low-light of this chapter is that the way memory was presented has already been deprecated. Therefore, the section needs additional follow-up attention.

- [**Chapter 4**](chapter4.ipynb) introduced the concept of chains, the main concept of LangChain, rooted in its name. Similar to the concepts of Chapter 4, the student is immediately greeted by deprecation warnings. I definitely need to look into how to use `runnable`.

- [**Chapter 5**](chapter5.ipynb) was about questions and answers. This was the chapter I most enjoyed, because I could re-create the mini-RAG scenario I had implemented for the Wittmann-Tours blog with just a few lines of code.

- [**Chapter 6**](chapter6.ipynb) talked about evaluations, something I had shamefully not touched with LLM applications before. I would definitely like to learn more about the subject, and the deprecation warnings and the transition to LangSmith, which has happened in the meantime, generate lots of opportunities to do just that.

- [**Chapter 7**](chapter7.ipynb) introduced agents, the LangChain way of giving tools to the LLM. Again, this is a section where LangChain shines because it delivers lots of tools out of the box without the need to implement them yourself. The solution of recreating my calculator application looks simple, but some strange error messages made me run in the completely wrong direction initially. This section has also evolved rapidly in LangChain and needs further attention.

Summing up, this was a great introduction to LangChain, something I wanted to explore for a long time. Thinking about this course as an introduction is exactly what it delivered, and it opened many opportunities for further exploration.

## Additional Learning

While I consider this course [done](https://medium.com/@bre/the-cult-of-done-manifesto-724ca1c2ff13), some chapters have raised additional questions and learning opportunities.

Here is a list of go-to topics I would like to explore in the future:

- **Explore the `runnable` Module**: Since `runnable` seems to be at the core of state-of-the-art chain implementations, I would like to dive into how it works and how to effectively use it in building chains.
  
- **Update on Memory Implementations**: Given that the memory approach presented in the course is now deprecated, I would like to explore the current best practices for implementing memory in LangChain to enable stateful conversations.
  
- **Deep Dive into Evaluations and LangSmith**: Testing is oftentimes underrated, but taking applications from prototypes to production requires extensive testing. From my perception, evaluations and LangSmith are the equivalent of automated testing in traditional programming. Therefore, I would like to dive deeper in this area.
  
- **Update on Agents and Tools**: Similar to memory, agents have evolved rapidly. Therefore, I would like to try out the state-of-the-art approaches to LangChain agents.
