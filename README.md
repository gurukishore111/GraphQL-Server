# GraphQL-Server

### MUTATION,QUERY

# QUERY

# query{
#    books{
#     id
#     name
#    }
# }

# query{
#    authors {
#      id
#     name
#    }
# }

# {
#   books {
#     author {
#       id
#       name
#     }
#   } 
# }

# {
#   authors {
#      name
#     books {
#       id
#       name
#     }
#   }
# }

# {
#   book(id:1){
#     id
#     name
#     author {
#       id
#       name
#     }
#   }
# }

# {
#   author(id:1){
#     id
#     name
#     books{
#       name
#       id
#     }
#   }
# }

#MUTATION

# mutation{
#   addBook(name:"NEW BOOK2",authorId:"1"){
#     id
#     name
#   }
# }

# mutation{
#   addAuthor(name:"DEV GK"){
#     id
#     name
#   }
# }
