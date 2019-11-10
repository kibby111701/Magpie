*I edited the code to convert all responses to lowercase in order to be able to respond to more phrases

keyword: i like     Response: that's epic, tell me more
keyword: obama      Response: what was his last name, tho?
keyword: joe        Response: joe momma


The reply method will reply with whatever phrase comes first in the method. For example, in the phrase "My mother has a dog", if the "mother" comes before "dog" in the reply method, it will reply with the "mother" response. If "dog" comes first, it will reply with the "dog" response

The problem is that the reply method can't tell when a word or phrase nested within another word, so it will reply with the corresponding response to the keyword even if it doesn't make sense.

