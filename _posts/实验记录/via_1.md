D:\Anaconda3\envs\TF2.6\python.exe E:\PycharmProjects\Recommender_system_via_deep_RL-main\evaluation.py 
E:\PycharmProjects\Recommender_system_via_deep_RL-main\evaluation.py:26: FutureWarning: Could not cast to uint32, falling back to object. This behavior is deprecated. In a future version, when a dtype is passed to 'DataFrame', either all columns will be cast to that dtype, or a TypeError will be raised.
  ratings_df = pd.DataFrame(ratings_list, columns=['UserID', 'MovieID', 'Rating', 'Timestamp'], dtype=np.uint32)
True
6040
6041 3953
4832 3953
4832 4832
1208 3953
1208 1208
2023-08-30 21:29:17.684233: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cudnn64_8.dll'; dlerror: cudnn64_8.dll not found
2023-08-30 21:29:17.684466: W tensorflow/core/common_runtime/gpu/gpu_device.cc:1835] Cannot dlopen some GPU libraries. Please make sure the missing libraries mentioned above are installed properly if you would like to use GPU. Follow the guide at https://www.tensorflow.org/install/gpu for how to download and setup the required libraries for your platform.
Skipping registering GPU devices...
2023-08-30 21:29:17.685065: I tensorflow/core/platform/cpu_feature_guard.cc:142] This TensorFlow binary is optimized with oneAPI Deep Neural Network Library (oneDNN) to use the following CPU instructions in performance-critical operations:  AVX AVX2
To enable them in other operations, rebuild TensorFlow with the appropriate compiler flags.
user_id : 4833, rated_items_length:81
history items : 
 [['Vacation (1983)' 'Comedy']
 ['Airplane II: The Sequel (1982)' 'Comedy']
 ['In the Heat of the Night (1967)' 'Drama|Mystery']
 ['Muppet Treasure Island (1996)' "Adventure|Children's|Comedy|Musical"]
 ['Braveheart (1995)' 'Action|Drama|War']
 ['Beauty and the Beast (1991)' "Animation|Children's|Musical"]
 ['Mad Max 2 (a.k.a. The Road Warrior) (1981)' 'Action|Sci-Fi']
 ['Silence of the Lambs, The (1991)' 'Drama|Thriller']
 ['Amadeus (1984)' 'Drama']
 ['Grapes of Wrath, The (1940)' 'Drama']]
recommended items ids : [1210  858  318 2762 2858  527 1196 1198 2028  260]
recommened items : 
 [['Star Wars: Episode VI - Return of the Jedi (1983)'
  'Action|Adventure|Romance|Sci-Fi|War']
 ['Godfather, The (1972)' 'Action|Crime|Drama']
 ['Shawshank Redemption, The (1994)' 'Drama']
 ['Sixth Sense, The (1999)' 'Thriller']
 ['American Beauty (1999)' 'Comedy|Drama']
 ["Schindler's List (1993)" 'Drama|War']
 ['Star Wars: Episode V - The Empire Strikes Back (1980)'
  'Action|Adventure|Drama|Sci-Fi|War']
 ['Raiders of the Lost Ark (1981)' 'Action|Adventure']
 ['Saving Private Ryan (1998)' 'Action|Drama|War']
 ['Star Wars: Episode IV - A New Hope (1977)'
  'Action|Adventure|Fantasy|Sci-Fi']]
precision : 0.3, dcg : 1.053, idcg : 4.544, ndcg : 0.232, reward : -0.5

precision : 0.3, ngcg : 0.23177307466786254, episode_reward : -0.5

user_id : 4834, rated_items_length:280
history items : 
 [['Star Wars: Episode VI - Return of the Jedi (1983)'
  'Action|Adventure|Romance|Sci-Fi|War']
 ['Silence of the Lambs, The (1991)' 'Drama|Thriller']
 ['Boxing Helena (1993)' 'Mystery|Romance|Thriller']
 ['Back to the Future (1985)' 'Comedy|Sci-Fi']
 ["Breakfast at Tiffany's (1961)" 'Drama|Romance']
 ['Mrs. Doubtfire (1993)' 'Comedy']
 ['Ponette (1996)' 'Drama']
 ['To Kill a Mockingbird (1962)' 'Drama']
 ['Central Station (Central do Brasil) (1998)' 'Drama']
 ['Godfather, The (1972)' 'Action|Crime|Drama']]
recommended items ids : [ 608 1221 2858 2028 1193  318 1198 1196  527  260]
recommened items : 
 [['Fargo (1996)' 'Crime|Drama|Thriller']
 ['Godfather: Part II, The (1974)' 'Action|Crime|Drama']
 ['American Beauty (1999)' 'Comedy|Drama']
 ['Saving Private Ryan (1998)' 'Action|Drama|War']
 ["One Flew Over the Cuckoo's Nest (1975)" 'Drama']
 ['Shawshank Redemption, The (1994)' 'Drama']
 ['Raiders of the Lost Ark (1981)' 'Action|Adventure']
 ['Star Wars: Episode V - The Empire Strikes Back (1980)'
  'Action|Adventure|Drama|Sci-Fi|War']
 ["Schindler's List (1993)" 'Drama|War']
 ['Star Wars: Episode IV - A New Hope (1977)'
  'Action|Adventure|Fantasy|Sci-Fi']]
precision : 0.8, dcg : 3.613, idcg : 4.544, ndcg : 0.795, reward : 6.0

precision : 0.8, ngcg : 0.7951657524814092, episode_reward : 6.0

user_id : 4835, rated_items_length:83
history items : 
 [['Dave (1993)' 'Comedy|Romance']
 ['Santa Clause, The (1994)' "Children's|Comedy|Fantasy"]
 ['Batman: Mask of the Phantasm (1993)' "Animation|Children's"]
 ["Amityville 1992: It's About Time (1992)" 'Horror']
 ['North by Northwest (1959)' 'Drama|Thriller']
 ['Just Cause (1995)' 'Mystery|Thriller']
 ['East of Eden (1955)' 'Drama']
 ['Sixth Sense, The (1999)' 'Thriller']
 ['L.A. Story (1991)' 'Comedy|Romance']
 ['Alien Nation (1988)' 'Crime|Drama|Sci-Fi']]
recommended items ids : [2396  260    1 1198 3114 1617 2028  318 2858  527]
recommened items : 
 [['Shakespeare in Love (1998)' 'Comedy|Romance']
 ['Star Wars: Episode IV - A New Hope (1977)'
  'Action|Adventure|Fantasy|Sci-Fi']
 ['Toy Story (1995)' "Animation|Children's|Comedy"]
 ['Raiders of the Lost Ark (1981)' 'Action|Adventure']
 ['Toy Story 2 (1999)' "Animation|Children's|Comedy"]
 ['L.A. Confidential (1997)' 'Crime|Film-Noir|Mystery|Thriller']
 ['Saving Private Ryan (1998)' 'Action|Drama|War']
 ['Shawshank Redemption, The (1994)' 'Drama']
 ['American Beauty (1999)' 'Comedy|Drama']
 ["Schindler's List (1993)" 'Drama|War']]
precision : 0.9, dcg : 4.254, idcg : 4.544, ndcg : 0.936, reward : 8.0

precision : 0.9, ngcg : 0.9363792118010483, episode_reward : 8.0

user_id : 4836, rated_items_length:65
history items : 
 [['Star Wars: Episode IV - A New Hope (1977)'
  'Action|Adventure|Fantasy|Sci-Fi']
 ['Splash (1984)' 'Comedy|Fantasy|Romance']
 ['Yellow Submarine (1968)' 'Animation|Musical']
 ['On Golden Pond (1981)' 'Drama']
 ['Stigmata (1999)' 'Thriller']
 ["They Shoot Horses, Don't They? (1969)" 'Drama']
 ['Patriot, The (2000)' 'Action|Drama|War']
 ['Myth of Fingerprints, The (1997)' 'Comedy|Drama']
 ['Before the Rain (Pred dozhdot) (1994)' 'Drama']
 ["Schindler's List (1993)" 'Drama|War']]
recommended items ids : [2997 2762  608  296   50 1617  593 2858  318  858]
recommened items : 
 [['Being John Malkovich (1999)' 'Comedy']
 ['Sixth Sense, The (1999)' 'Thriller']
 ['Fargo (1996)' 'Crime|Drama|Thriller']
 ['Pulp Fiction (1994)' 'Crime|Drama']
 ['Usual Suspects, The (1995)' 'Crime|Thriller']
 ['L.A. Confidential (1997)' 'Crime|Film-Noir|Mystery|Thriller']
 ['Silence of the Lambs, The (1991)' 'Drama|Thriller']
 ['American Beauty (1999)' 'Comedy|Drama']
 ['Shawshank Redemption, The (1994)' 'Drama']
 ['Godfather, The (1972)' 'Action|Crime|Drama']]
precision : 0.4, dcg : 1.950, idcg : 4.544, ndcg : 0.429, reward : 1.0

precision : 0.4, ngcg : 0.42914113378860647, episode_reward : 1.0

user_id : 4837, rated_items_length:328
history items : 
 [['Kiss of Death (1995)' 'Crime|Drama|Thriller']
 ['Operation Condor (Feiying gaiwak) (1990)' 'Action|Adventure|Comedy']
 ['Braveheart (1995)' 'Action|Drama|War']
 ['Rocky II (1979)' 'Action|Drama']
 ['Original Gangstas (1996)' 'Crime']
 ['Sixth Sense, The (1999)' 'Thriller']
 ['Nightmare on Elm Street 5: The Dream Child, A (1989)' 'Horror']
 ['New Jersey Drive (1995)' 'Crime|Drama']
 ['Star Wars: Episode VI - Return of the Jedi (1983)'
  'Action|Adventure|Romance|Sci-Fi|War']
 ['Assault on Precinct 13 (1976)' 'Action|Thriller']]
recommended items ids : [1200  589 1198 1214  260 1196 1270 2571 1240 1097]
recommened items : 
 [['Aliens (1986)' 'Action|Sci-Fi|Thriller|War']
 ['Terminator 2: Judgment Day (1991)' 'Action|Sci-Fi|Thriller']
 ['Raiders of the Lost Ark (1981)' 'Action|Adventure']
 ['Alien (1979)' 'Action|Horror|Sci-Fi|Thriller']
 ['Star Wars: Episode IV - A New Hope (1977)'
  'Action|Adventure|Fantasy|Sci-Fi']
 ['Star Wars: Episode V - The Empire Strikes Back (1980)'
  'Action|Adventure|Drama|Sci-Fi|War']
 ['Back to the Future (1985)' 'Comedy|Sci-Fi']
 ['Matrix, The (1999)' 'Action|Sci-Fi|Thriller']
 ['Terminator, The (1984)' 'Action|Sci-Fi|Thriller']
 ['E.T. the Extra-Terrestrial (1982)' "Children's|Drama|Fantasy|Sci-Fi"]]
precision : 0.2, dcg : 0.764, idcg : 4.544, ndcg : 0.168, reward : -2.0

precision : 0.2, ngcg : 0.1681522864689108, episode_reward : -2.0

user_id : 4838, rated_items_length:39
history items : 
 [['Adventures of Milo and Otis, The (1986)' "Children's"]
 ['Honey, I Shrunk the Kids (1989)'
  "Adventure|Children's|Comedy|Fantasy|Sci-Fi"]
 ['Gone with the Wind (1939)' 'Drama|Romance|War']
 ['Aladdin and the King of Thieves (1996)' "Animation|Children's|Comedy"]
 ["Schindler's List (1993)" 'Drama|War']
 ['Adventures of Rocky and Bullwinkle, The (2000)'
  "Animation|Children's|Comedy"]
 ['Chicken Run (2000)' "Animation|Children's|Comedy"]
 ['Paulie (1998)' "Adventure|Children's|Comedy"]
 ['Dances with Wolves (1990)' 'Adventure|Drama|Western']
 ['Secret of Roan Inish, The (1994)' 'Drama']]
recommended items ids : [   1  593 2396 2324 2028 1704  356 1784 2858  318]
recommened items : 
 [['Toy Story (1995)' "Animation|Children's|Comedy"]
 ['Silence of the Lambs, The (1991)' 'Drama|Thriller']
 ['Shakespeare in Love (1998)' 'Comedy|Romance']
 ['Life Is Beautiful (La Vita è bella) (1997)' 'Comedy|Drama']
 ['Saving Private Ryan (1998)' 'Action|Drama|War']
 ['Good Will Hunting (1997)' 'Drama']
 ['Forrest Gump (1994)' 'Comedy|Romance|War']
 ['As Good As It Gets (1997)' 'Comedy|Drama']
 ['American Beauty (1999)' 'Comedy|Drama']
 ['Shawshank Redemption, The (1994)' 'Drama']]
precision : 0.2, dcg : 0.720, idcg : 4.544, ndcg : 0.158, reward : -2.0

precision : 0.2, ngcg : 0.1584091525685025, episode_reward : -2.0

user_id : 4839, rated_items_length:23
history items : 
 [['Papillon (1973)' 'Drama']
 ['Sleeper (1973)' 'Comedy|Sci-Fi']
 ['Dave (1993)' 'Comedy|Romance']
 ['Braveheart (1995)' 'Action|Drama|War']
 ['Get Shorty (1995)' 'Action|Comedy|Drama']
 ['Titanic (1997)' 'Drama|Romance']
 ['Limey, The (1999)' 'Action|Crime|Drama']
 ['Sixth Sense, The (1999)' 'Thriller']
 ['Insider, The (1999)' 'Drama']
 ['American Beauty (1999)' 'Comedy|Drama']]
recommended items ids : [1704    1 1784  593 2396  318  527 2028  356 2324]
recommened items : 
 [['Good Will Hunting (1997)' 'Drama']
 ['Toy Story (1995)' "Animation|Children's|Comedy"]
 ['As Good As It Gets (1997)' 'Comedy|Drama']
 ['Silence of the Lambs, The (1991)' 'Drama|Thriller']
 ['Shakespeare in Love (1998)' 'Comedy|Romance']
 ['Shawshank Redemption, The (1994)' 'Drama']
 ["Schindler's List (1993)" 'Drama|War']
 ['Saving Private Ryan (1998)' 'Action|Drama|War']
 ['Forrest Gump (1994)' 'Comedy|Romance|War']
 ['Life Is Beautiful (La Vita è bella) (1997)' 'Comedy|Drama']]
precision : 0.0, dcg : 0.000, idcg : 4.544, ndcg : 0.000, reward : -5.0

precision : 0.0, ngcg : 0.0, episode_reward : -5.0

user_id : 4840, rated_items_length:72
history items : 
 [['Midnight in the Garden of Good and Evil (1997)'
  'Comedy|Crime|Drama|Mystery']
 ['E.T. the Extra-Terrestrial (1982)' "Children's|Drama|Fantasy|Sci-Fi"]
 ['L.A. Confidential (1997)' 'Crime|Film-Noir|Mystery|Thriller']
 ['Karate Kid III, The (1989)' 'Action|Adventure|Drama']
 ['Forrest Gump (1994)' 'Comedy|Romance|War']
 ['True Grit (1969)' 'Adventure|Western']
 ['Searchers, The (1956)' 'Western']
 ['Butch Cassidy and the Sundance Kid (1969)' 'Action|Comedy|Western']
 ['Unforgiven (1992)' 'Western']
 ['Dances with Wolves (1990)' 'Adventure|Drama|Western']]
recommended items ids : [3114 1704    1  593 1265 2396  318 2028  527 2858]
recommened items : 
 [['Toy Story 2 (1999)' "Animation|Children's|Comedy"]
 ['Good Will Hunting (1997)' 'Drama']
 ['Toy Story (1995)' "Animation|Children's|Comedy"]
 ['Silence of the Lambs, The (1991)' 'Drama|Thriller']
 ['Groundhog Day (1993)' 'Comedy|Romance']
 ['Shakespeare in Love (1998)' 'Comedy|Romance']
 ['Shawshank Redemption, The (1994)' 'Drama']
 ['Saving Private Ryan (1998)' 'Action|Drama|War']
 ["Schindler's List (1993)" 'Drama|War']
 ['American Beauty (1999)' 'Comedy|Drama']]
precision : 0.5, dcg : 2.152, idcg : 4.544, ndcg : 0.474, reward : 1.5

precision : 0.5, ngcg : 0.4736695902179647, episode_reward : 1.5

user_id : 4841, rated_items_length:92
history items : 
 [['Forrest Gump (1994)' 'Comedy|Romance|War']
 ['Mulholland Falls (1996)' 'Crime|Film-Noir|Thriller']
 ['Princess Bride, The (1987)' 'Action|Adventure|Comedy|Romance']
 ['Hook (1991)' 'Adventure|Fantasy']
 ['Casino (1995)' 'Drama|Thriller']
 ['Raiders of the Lost Ark (1981)' 'Action|Adventure']
 ['Croupier (1998)' 'Crime|Drama']
 ['Chicken Run (2000)' "Animation|Children's|Comedy"]
 ['Hamlet (2000)' 'Drama']
 ['Big Kahuna, The (2000)' 'Comedy|Drama']]
recommended items ids : [2997  296 2571 1214  593  541 1196 2858  260  858]
recommened items : 
 [['Being John Malkovich (1999)' 'Comedy']
 ['Pulp Fiction (1994)' 'Crime|Drama']
 ['Matrix, The (1999)' 'Action|Sci-Fi|Thriller']
 ['Alien (1979)' 'Action|Horror|Sci-Fi|Thriller']
 ['Silence of the Lambs, The (1991)' 'Drama|Thriller']
 ['Blade Runner (1982)' 'Film-Noir|Sci-Fi']
 ['Star Wars: Episode V - The Empire Strikes Back (1980)'
  'Action|Adventure|Drama|Sci-Fi|War']
 ['American Beauty (1999)' 'Comedy|Drama']
 ['Star Wars: Episode IV - A New Hope (1977)'
  'Action|Adventure|Fantasy|Sci-Fi']
 ['Godfather, The (1972)' 'Action|Crime|Drama']]
precision : 0.6, dcg : 2.893, idcg : 4.544, ndcg : 0.637, reward : 2.5

precision : 0.6, ngcg : 0.636658712740428, episode_reward : 2.5

user_id : 4842, rated_items_length:69
history items : 
 [['Plan 9 from Outer Space (1958)' 'Horror|Sci-Fi']
 ['Casablanca (1942)' 'Drama|Romance|War']
 ['EDtv (1999)' 'Comedy']
 ['Princess Bride, The (1987)' 'Action|Adventure|Comedy|Romance']
 ['Irma la Douce (1963)' 'Comedy']
 ['American Tail, An (1986)' "Animation|Children's|Comedy"]
 ['American Beauty (1999)' 'Comedy|Drama']
 ['Being John Malkovich (1999)' 'Comedy']
 ['Sixth Sense, The (1999)' 'Thriller']
 ['Limey, The (1999)' 'Action|Crime|Drama']]
recommended items ids : [1213 1617  111  593  296  858  527 1193  318  608]
recommened items : 
 [['GoodFellas (1990)' 'Crime|Drama']
 ['L.A. Confidential (1997)' 'Crime|Film-Noir|Mystery|Thriller']
 ['Taxi Driver (1976)' 'Drama|Thriller']
 ['Silence of the Lambs, The (1991)' 'Drama|Thriller']
 ['Pulp Fiction (1994)' 'Crime|Drama']
 ['Godfather, The (1972)' 'Action|Crime|Drama']
 ["Schindler's List (1993)" 'Drama|War']
 ["One Flew Over the Cuckoo's Nest (1975)" 'Drama']
 ['Shawshank Redemption, The (1994)' 'Drama']
 ['Fargo (1996)' 'Crime|Drama|Thriller']]
precision : 0.3, dcg : 0.991, idcg : 4.544, ndcg : 0.218, reward : -1.0

precision : 0.3, ngcg : 0.2180164145324244, episode_reward : -1.0

user_id : 4843, rated_items_length:116
history items : 
 [['Fatal Attraction (1987)' 'Thriller']
 ['Jurassic Park (1993)' 'Action|Adventure|Sci-Fi']
 ['Mrs. Brown (Her Majesty, Mrs. Brown) (1997)' 'Drama|Romance']
 ['Moonstruck (1987)' 'Comedy']
 ['Back to the Future (1985)' 'Comedy|Sci-Fi']
 ['Blowup (1966)' 'Drama|Mystery']
 ['Hamlet (1990)' 'Drama']
 ['Tango (1998)' 'Drama']
 ['400 Blows, The (Les Quatre cents coups) (1959)' 'Drama']
 ['Godfather, The (1972)' 'Action|Crime|Drama']]
recommended items ids : [1207   36  912  919 2858  608 1247 1193  527  318]
recommened items : 
 [['To Kill a Mockingbird (1962)' 'Drama']
 ['Dead Man Walking (1995)' 'Drama']
 ['Casablanca (1942)' 'Drama|Romance|War']
 ['Wizard of Oz, The (1939)' "Adventure|Children's|Drama|Musical"]
 ['American Beauty (1999)' 'Comedy|Drama']
 ['Fargo (1996)' 'Crime|Drama|Thriller']
 ['Graduate, The (1967)' 'Drama|Romance']
 ["One Flew Over the Cuckoo's Nest (1975)" 'Drama']
 ["Schindler's List (1993)" 'Drama|War']
 ['Shawshank Redemption, The (1994)' 'Drama']]
precision : 0.4, dcg : 1.505, idcg : 4.544, ndcg : 0.331, reward : 0.0

precision : 0.4, ngcg : 0.3312392961638527, episode_reward : 0.0

user_id : 4844, rated_items_length:29
history items : 
 [["Jumpin' Jack Flash (1986)" 'Action|Comedy|Romance|Thriller']
 ['Star Wars: Episode VI - Return of the Jedi (1983)'
  'Action|Adventure|Romance|Sci-Fi|War']
 ['McCabe & Mrs. Miller (1971)' 'Drama|Western']
 ['L.A. Confidential (1997)' 'Crime|Film-Noir|Mystery|Thriller']
 ['Mrs. Winterbourne (1996)' 'Comedy|Romance']
 ["Gentleman's Agreement (1947)" 'Drama']
 ['American Beauty (1999)' 'Comedy|Drama']
 ['Talented Mr. Ripley, The (1999)' 'Drama|Mystery|Thriller']
 ['World Is Not Enough, The (1999)' 'Action|Thriller']
 ['Star Wars: Episode I - The Phantom Menace (1999)'
  'Action|Adventure|Fantasy|Sci-Fi']]
recommended items ids : [2324 2396  608  356  593 1704  110 2028  318  527]
recommened items : 
 [['Life Is Beautiful (La Vita è bella) (1997)' 'Comedy|Drama']
 ['Shakespeare in Love (1998)' 'Comedy|Romance']
 ['Fargo (1996)' 'Crime|Drama|Thriller']
 ['Forrest Gump (1994)' 'Comedy|Romance|War']
 ['Silence of the Lambs, The (1991)' 'Drama|Thriller']
 ['Good Will Hunting (1997)' 'Drama']
 ['Braveheart (1995)' 'Action|Drama|War']
 ['Saving Private Ryan (1998)' 'Action|Drama|War']
 ['Shawshank Redemption, The (1994)' 'Drama']
 ["Schindler's List (1993)" 'Drama|War']]
precision : 0.3, dcg : 1.464, idcg : 4.544, ndcg : 0.322, reward : -1.0

precision : 0.3, ngcg : 0.3222722491219547, episode_reward : -1.0

precision@10 : 0.4083333333333334, ndcg@10 : 0.39173973954608043
