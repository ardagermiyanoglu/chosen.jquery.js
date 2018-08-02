# chosen.jquery.js
Turkish character ('İ') fixed.

code added to the 340th line

if (query[0] == 'i') {
    query = query[0].replace('i', 'İ') + query.slice(1);
    console.log(query);
}
