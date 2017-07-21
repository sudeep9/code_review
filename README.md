# code_review
A checklist for code reviewers

# What is this about?

During my career I have been part of lot of discussions about code reviews and a general consensus is that it is a good practice but it is hard. Then there are discussions about "effective code review". A google search on this will yield a lot of results and on youtube one will find lots of tech-talks on this topic. Most of them have good advice and some of the top things are:

1. Need for better tools (e.g linter/static checkers) to find common/micro mistakes
2. Need for reviewing system (e.g. Gerrit)
3. Play nice i.e. be constructive, solve problems and do not critisize

All of these are fine and the points are well taken. However, rarely I have seen the any discussion about the actual process of reviewing the code from a reviewer's point of view. So this doc is essentially addressing the problem "Given a code in front of me, how should I go about reviewing the code?". In other words, "can we bring some structure to actual act of code review?". This document tries to be very specific in scope and therefore the assumes the following:

1. You are aware of the context in which change is proposed . This means that you know the feature request. You have been part of design discussions. 
