## Act report.

The confidence of the algorithm decreases across the first, second, and third predictions. Images returned for the first prediction made by the neural network can always be trusted more to be accurate than the ones returned by the second and third predictions. Evidently, the mean of the confidence of the first prediction was greater than that of the mean of the confidence of the second and third predictions combined!
So working with the values of the first prediction sounds reasonable. 

The top 10 breeds of dogs predicted correctly by the first prediction in descending order are Clumber, Brittany Spaniel. Keeshond, Pomeranian, French Bulldog, Bull Mastiff, Bernese Mountain Dog, German Short-Haired Pointer, Pug, and Vizsla with confidence between 94% -74%. The top 10 breeds of dogs predicted correctly for the first prediction in descending order are Brabancon Griffon, Norfolk Terrier, Bedlington Terrier, Silky Terrier, Australian Terrier, Mexican Hairless, Norwich Terrier, Cairn, Scotch Terrier, Scottish Deerhound with a confidence range between 36% - 18%. The algorithm of the neural network for identifying breeds of dogs in pictures can be trusted to predict accurately a picture having Clumber, Spaniel. Keeshond, Pomeranian, Bulldog, Mastiff, Mountain Dog, Short-Haired Pointer, Pug, and Vizsla but seems to have an issue with identifying Terrier with high confidence because 6 breeds of Terrier were in the list of 10 dogs with the lowest confidence. The algorithm should probably be retrained with more image data of Terriers.

Standard Poodle, Eskimo Dog, English Springer, Irish Water Spaniel, Saluki, Cardigan, French Bulldog, Samoyed, Great Pyrenees, and Lakeland Terrier are the top 10 breeds of dogs that had mean highest retweets in the first prediction. Irish Water Spaniel, Saluki, Standard Poodle, French Bulldog, Black and Tan Coonhound, Flat-Coated Retriever, Eskimo Dog, English Springer, Lakeland Terrier, and Cardigan are the top 10 breeds of dogs with the mean highest favorite counts in the first prediction. Scottish Deerhound, Soft-Coated Wheaten Terrier, Entlebucher, Welsh Springer Spaniel, Japanese Spaniel, Ibizan Hound, Groenenhoel, Tibetan Terrier, Cairn, and Brabancon Griffon are the top 10 breeds of dogs with the mean lowest retweets counts. Basenji, Scottish Deerhound, Soft-Coated Wheaten Terrier, Standard Schnauzer, Groenenhoel, Tibetan Terrier, Japanese Spaniel, Cairn, Ibizan Hound, and Brabancon Griffon are the top 10 breeds of dogs with the mean lowest favorite counts. 8 breeds of dogs are both in the list of the top 10 breeds with the mean highest retweets and favorite counts. Also, 8 breeds of dogs appeared in the list of the top 10 breeds of dogs with the mean lowest retweets and favorite counts. This begs the question, Is there a relationship between retweets and favorites?

Dogs with high retweets counts have high favorite counts irrespective of the accuracy/confidence of the image prediction algorithm. A scatterplot of retweet counts and favorite counts further confirms the thought that breeds of dogs with high retweets have high favorite counts and vice versa. This could be further confirmed with the mathematical computation of the relationship between retweet counts and favorite counts, the correlation value is 0.93 suggesting a strong positive relationship. Although a high correlation does not necessarily mean causation it can be known that if a picture of a dog is posted on the @weratedogs timeline if it gets to have a high number of retweets then it will have a high number of favorite counts and vice versa.

The most popular dog stage with known status posted on the @weratedog is PUPPER.