Run

    docker build . -t pres-eks-features:latest
    docker run --rm -p 8080:8000 pres-eks-features

Develop

    docker run -d --rm -p 8080:8000 -v $HOME/Development/presentations/eks-features/presentation:/presentation pres-eks-features:latest
