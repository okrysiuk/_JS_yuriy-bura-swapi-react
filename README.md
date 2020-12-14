// https://swapi.dev/
// https://bootswatch.com/
// https://regex101.com/
// https://loading.io/

сomponentDidMount() -> метод жизненного цикла выполняется после того, как компонент отрисуется на странице первый раз. Хорошее место для получения данных с сервера.

componentWillUnmout() -> метод жизненного цикла выполняется перед удалением компонента со страницы.

## MOUNTING

constructor() -> render() -> componentDidMount()

## UPDATES

( New Props || setState() ) -> render() -> componentDidUpdate(prevProps, prevState)

## UNMOUNTING

componentWillUnmount()

## ERRORS

componentDidCatch(error, info)
